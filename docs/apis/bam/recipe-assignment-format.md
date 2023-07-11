---
title: "Format: Recipe Assignment"
layout: default
parent: "BUNN Asset Management API"
grand_parent: "BUNN APIs"
has_children: false
nav_order: 6
---

# Recipe Assignment Format

## Validations

### Fully-defined Schedule

- All days of the week must be present
- All times of day must be present

## Example

```
{
  "externalId": "string",
  "schedules": [
    {
      "applicableRecipeNames": [
        "string"
      ],
      "scheduleLabel": "string",
      "segmentGroups": [
        {
          "daysOfWeek": [
            "FRIDAY"
          ],
          "segments": [
            {
              "endTimeLocal24": "string",
              "holdVolumeOz": 0,
              "resetAgeAfterTopOff": true,
              "startTimeLocal24": "string"
            }
          ]
        }
      ]
    }
  ],
  "serialNumbers": [
    "string"
  ]
}
```

## JSON Schema
```
// JSON Schedule document must have top array
[
    {
        "serialNumbers": [                            // optional serial Number
            ""
        ],
        "schedules": [                                // required schedule (array)
            {
                "applicableRecipeNames": [            // require recipe or list (array, string)
                    "CINNAMON BUN"
                ],
                "isModifiedTemplate": false,          // internal use - optional
                "isReadOnly": false,                  // internal use - optional
                "isTemplate": false,                  // internal use - optional
                "scheduleLabel": "Average Volume",    // optional label, "" if omitted
                "holdVolumeOz": 0,                    // optional override
                "resetAgeAfterTopOff": false,         // optional override
                "segmentGroups": [                    // day segment definition (array)
                    {
                        "holdVolumeOz": 0,            // optional override
                        "resetAgeAfterTopOff": false, // optional override
                        "daysOfWeek": [               // Day of week (array) - all days of week must be present in the
                                                       // segmentGroups array
                            "Sunday",
                            "Friday",
                            "Thursday",
                            "Wednesday",
                            "Tuesday",
                            "Monday",
                            "Saturday"
                        ],
                        "segments": [                 // must include every hour of day, or a higher level holdVolume and
                                                       // reset Age AfterTopOff                                                                                                                                                                  {
                                "endTimeLocal24": "24:00",      // exclusive
                                "holdVolumeOz": 0,              // can be replaced with higher level overrides
                                "resetAgeAfterTopOff": false,   // can be replaced with higher level overrides
                                "startTimeLocal24": "00:00"     // inclusive
                            }
                        ]
                    }
                ]
            }
        ]
    }
]
```