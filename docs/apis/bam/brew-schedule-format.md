---
title: "Format: Brew Schedule"
layout: default
parent: "BUNN Asset Management API"
grand_parent: "BUNN APIs"
has_children: false
nav_order: 4
---

# Brew Schedule Request Format
{: .no_toc }

This document describes the required format for submitting Brew Schedules to machines via the BUNN Asset Management API.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## JSON Schema
```
[ // JSON Schedule document must have top array
  {
    "serialNumbers": [                            // optional serial Number
      ""
    ],
    "schedules": [                                // required schedule (array)
      {
        "applicableRecipeNames": [            // require recipe or list (array, string)
          "CINNAMON BUN"
        ],
        "scheduleLabel": "Average Volume",    // optional label, "" if omitted
        "holdVolumeOz": 0,                    // optional override
        "resetAgeAfterTopOff": false,         // optional override
        "segmentGroups": [                    // day segment definition (array)
          {
            "holdVolumeOz": 0,            // optional override
            "resetAgeAfterTopOff": false, // optional override
            "daysOfWeek": [               // Day of week (array) - all days of week must be present in the segmentGroups array
              "Sunday",
              "Monday",
              "Tuesday",
              "Wednesday",
              "Thursday",
              "Friday",
              "Saturday"
            ],
            "segments": [ // must include every hour of day, or a higher level holdVolume and reset Age After TopOff 
              {
                "startTimeLocal24": "00:00"     // inclusive
                "endTimeLocal24": "24:00",      // exclusive
                "holdVolumeOz": 0,              // can be replaced with higher level overrides
                "resetAgeAfterTopOff": false,   // can be replaced with higher level overrides
              }
            ]
          }
        ]
      }
    ]
  }
]
```

## Payload Breakdown

### Request 
The request contains all the information required to set Brewing Schedules for a particular set of machines.

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| serialNumbers | String Array | ["SN1", "SN2"] | The set of Serial Numbers on which to create/update the schedules. |
| schedules | Schedule Array | [ {schedule-1}, {schedule-2} ] | The set of schedules to create/update on the specified machines. See Schedule section below. |
| externalId | String | "customer-defined-id" | Optional. Customer-defined ID which allows searching the BUNN APIs for this request by your own ID. (Pending feature) |

### Schedule

The schedule contains the brew schedule settings for a machine over a week of operation. It also provides a means to apply settings across an entire schedule.

An example of a schedule in plain English would be:

- On weekdays (M-F), apply schedule A.
- On weekends, apply schedule B.
- Regardless of day or time, always reset the freshness timer when new coffee is brewed.

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| scheduleLabel | String | "Weekday Schedule" | Label for the schedule which is referenced by Recipe Assignements |
| applicableRecipeNames | String Array | ["Regular", "Decaf"] | The set of Recipes to which this schedule may be applied |
| holdVolumeOz | Integer | 128 | Optional. Sets the default amount of coffee to maintain in the reservoir across the whole schedule. Will be applied to all segments in the schedule. |
| resetAgeAfterTopOff | Boolean | true | Optional. Sets the resetAgeAfterTopOff indicator across the whole schedule. Will be applied to all segments in the schedule. <br><br>This indicator determines if new coffee brewed and funneled into a non-empty reservoir will reset the freshness timer. 'true' will reset the timer, 'false' will maintain the timer since the first brew still in the reservoir. |
| segmentGroups | Segment Group Array | [ {segment-group-1}, {segment-group-2} ] | The set of Segment Groups in the schedule. Segment Groups contain one or more Segments along with applicable days of the week and default settings. See Segment Group section below. |

### Segment Group

The 'Segment Group' aggregates one or more 'Segments' (settings for a range of time) into a daily schedule and applies that daily schedules to a set of days. It also provides a means to apply default settings to all aggregated segments to ease repetition.

An example of a Segment Group in plain english would be:

- Daily Schedule:
  - Keep the reservoir empty from midnight until 5 AM
  - Then maintain 128 oz of coffee in the reservoir from 5 AM until 5 PM
  - Then maintain 32 oz of coffee from 5 PM until 10 PM
  - Then drain the reservoir and keep it empty from 10 PM until midnight
- Apply this schedule every weekday (Monday - Friday).
- On these days (weekdays), never reset the Freshness Timer when new coffee is brewed if there is still old coffee in the reservoir.

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| holdVolumeOz | Integer | 128 | Optional. Sets the default amount of coffee to maintain in the reservoir across all Segments in this Segment Group. |
| resetAgeAfterTopOff | Boolean | true | Optional. Sets the resetAgeAfterTopOff indicator across all Segments in the Segment Group. <br><br>This indicator determines if new coffee brewed and funneled into a non-empty reservoir will reset the freshness timer. 'true' will reset the timer, 'false' will maintain the timer since the first brew still in the reservoir. |
| daysOfWeek | String Array | [ "Sunday", "Saturday" ] | The days of the week to which to apply the "Daily Schedule" as represented by the collection of Segments. |
| segments | Segment Array | [ {segment-1}, {segment-2} ] | This collection represents a "Daily Schedule" containing brew settings (such as hold volume) for time ranges throughout a day. |

### Segment

The 'Segment' is the primary unit of scheduling for a day. It captures the brewing settings that apply for a particular range of time.

An example of a Segment in plain english would be:

"From 5 AM until 5 PM, maintain 128 oz of coffee in the reservoir and reset the Freshness Timer each time new coffee is brewed."

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| startTimeLocal24 | Time (HH:mm) | 00:00 | The start time (inclusive) for this segment as expressed in hours and minutes. Hours are expressed as 00 to 24. Minutes are expressed as 00 to 59. Times are local to the machine's configured Time Zone. |
| endTimeLocal24 | Time (HH:mm) | 24:00 | The end time (exclusive) for this segment as expressed in hours and minutes. Hours are expressed as 00 to 24. Minutes are expressed as 00 to 59. Times are local to the machine's configured Time Zone. |
| holdVolumeOz | Integer | 128 | Optional if set at higher level. Sets the amount of coffee to maintain in the reservoir for this Segment's time range. |
| resetAgeAfterTopOff | Boolean | true | Optional if set at higher level. Sets the resetAgeAfterTopOff indicator for this Segment's time range. <br><br>This indicator determines if new coffee brewed and funneled into a non-empty reservoir will reset the freshness timer. 'true' will reset the timer, 'false' will maintain the timer since the first brew still in the reservoir. |

## Data Requirements / Validations

### Serial Numbers

- Serial Numbers must be valid and registered in BUNNlink / BUNNcloud
- Serial Numbers must be registered the the user account making the request

### Schedules

- Recipe Names must match recipes defined on the machine
- Schedule Labels must match schedule labels defined on the machine
- Fully-defined Schedule
  - All days of the week must be accounted for
  - All times of day (hours/minutes) must be accounted for
- holdVolumeOz must be set for each Segment. This can be set directly at the Segment level or inherited from a Segment Group or Schedule.
- resetAgeAtTopOff must be set for each Segment. This can be set directly at the Segment level or inherited from a Segment Group or Schedule.

## Example

```
[
  {
    "externalId" : "<your-id-for-this-schedule>",
    "serialNumbers": [
      "SN123ABC",
      "SNA1B2C3D4E5"
    ],
    "schedules": [
      {
        "scheduleLabel": "All Day, Every Day!",
        "applicableRecipeNames": [
          "Regular",
          "Decaf"
        ],
        "segmentGroups": [
          {
            "daysOfWeek": [
              "Sunday",
              "Monday",
              "Tuesday",
              "Wednesday",
              "Thursday",
              "Friday",
              "Saturday"
            ],
            "segments": [
              {
                "startTimeLocal24": "00:00",
                "endTimeLocal24": "24:00",
                "holdVolumeOz": 128,
                "resetAgeAfterTopOff": false
              }
            ]
          }
        ]
      }
    ]
  }
]
```