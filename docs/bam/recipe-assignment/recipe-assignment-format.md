---
title: "Format"
layout: default
parent: "Recipe Assignment"
grand_parent: "BUNN Asset Management API"
has_children: false
nav_order: 2
---

# Recipe Assignment Request Format
{: .no_toc }

This document describes the required format for submitting Recipe Assignments to machines via the BUNN Asset Management API.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## JSON Schema
```
// JSON Assignment document must have top object
{
  "externalId": "user-defined-id", // User-defined ID used for querying and tracking
  "stores": [  // optional store array
    {
      "storeNumber": 8083,  // optional store tag - unused by machine
      "assignments": [  // required assignments array
        {
          "serialNumber": "BTB0000001",  // optional Serial Number to specify machine (string)
          // General Rules:  Can not duplicate Reservoir position
          //                 Up to 3 reservoir positions
          //                 Duplicate Reservoir Recipe assignments are valid
          "reservoirs": [  // optional reservoir assignments (ARRAY)
            {
              "identifier": 1,  // identifier that matches the reservoir alias list (string or int)
              "recipeName": "REGULAR",  // Recipe Name that must be present on machine (string), blank is disabled/unassigned
              "scheduleLabel": "PRIMARY"  // Schedule label that must be on machine for that recipe (string) - optional blank if omitted
            },
            {
              "identifier": 2,
              "recipeName": "CUBAN",
              "scheduleLabel": "PRIMARY"
            },
            {
              "identifier": 3,
              "recipeName": "DARK ROAST",
              "scheduleLabel": "PRIMARY"
            }
          ],
          // General Rules:  Can not duplicate Hopper position
          //                 Up to 3 hopper positions
          //                 Duplicate product assignments are valid
          "hoppers": [  // optional hopper assignments (ARRAY)
            {
              "identifier": 1,  // identifier that matches the hopper alias list (string or int)
              "productName": "REGULAR"  // Product Name that must be present on machine  (string)
            },
            {
              "identifier": 2,
              "productName": "CUBAN"
            },
            {
              "identifier": 3,
              "productName": "DARK ROAST"
            }
          ],
          // General Rules:  Can not duplicate Associate Dispense position
          //                 Duplicate recipe assignments are valid
          "associateDispense": [  // optional Associate Dispence assignments (ARRAY)
            {
                "identifier": "1",  // identifier that conveys the sort order of the recipes (string or int)
                "recipeName": "CUBAN"  // recipe name that must be present on machine and be unique within this assignment (string)
            },
            {
                "identifier": "2",
                "recipeName": "REGULAR"
            },
            {
                "identifier": "3",
                "recipeName": "DARK ROAST"
            }
          ]
        }
      ]
    }
  ]
}
```

## Payload Breakdown

### Request 
The request contains all the information required to set Recipe Assignments for a set of locations and corresponding machines.

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| stores | Store Array | [ {store1}, {store2} ] | The set of stores which will have Recipe Assignments pushed. See Store section below. |
| externalId | String | "customer-defined-id" | Optional. Customer-defined ID which allows searching the BUNN APIs for this request by your own ID. (Pending feature) |

### Store (Location)

This object contains the Recipe Assignments for a particular store (Location).

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| storeNumber | String | "1234" | Label for the store to which the Recipe Assignements will be applied. This is not used by the BUNN APIs but included for user convenience. |
| assignments | Assignment Array | [ {assignment-1}, {assignment-2} ] | The set of Assignments to apply. There should be 1 Assignment per machine in the store. See the Assignment section below. |

### Assignment

The Assignment contains configurations for a particular machine for one or more of:

- Reservoir Assignments
- Hopper Assignments
- Associate Dispense Menu Assignments 

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| serialNumber | String | "SN1234" | The unique identifier of the machine on which to create/update the Assignment. |
| reservoirs | Reservoir Array | [ {reservoir-1}, {reservoir-2} ] | Optional. This collection holds the Reservoir configurations for the machine. See Reservoir Configuration section below. |
| hoppers | Hopper Array | [ {hopper-1}, {hopper-2} ] | Optional. This collection holds the Hopper configurations for the machine. See Hopper Configuration section below. |
| associateDispense | Associate Dispense Array | [ {associate-dispense-1}, {associate-dispense-2} ] | Optional. This collection holds the Associate Dispense configurations for the machine. See Associate Dispense Configuration section below. |

### Reservoir Configuration

The Reservoir Configuration associates a recipe to a reservoir and a brewing schedule.

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| identifier | String | "1" | Identifies the reservoir to configure. Must match an entry in the machine's reservoir alias list. Must be unique per Assignment. |
| recipeName | String | "REGULAR" | The Recipe Name to assign to the Reservoir. Recipe must be present on machine. Passing blank will disable/unassign the reservoir. |
| scheduleLabel | String | "PRIMARY" | Optional. Identifies the Brew Schedule to assign to the Reservoir / Recipe. The Schedule Label that must be present on machine and enabled that recipe (see more about [pushing Brew Schedules](../brew-schedule/brew-schedule-usage)). |

### Hopper Configuration

The Hopper Configuration associates a product (bean) to a machine hopper. These assignments are necessary for the machine to know which hopper holds the required beans for its programmed recipes.

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| identifier | String | "1" | Identifies the hopper to configure. Must match an entry in the machine's hopper alias list. |
| productName | String | "REGULAR" | The Product Name to assign to the Hopper. Product must be present on machine. |

### Associate Dispense Configuration

The Associate Dispense configuration associates a recipe to a display slot on the Associate Dispense menu.

#### Details
{: .no_toc }

|Field|Type|Example|Description|
|:--|:--|:--|:--|
| identifier | String | "1" | Identifies the Associate Menu "slot" (sort order) to configure. Must be unique per assignment. |
| recipeName | String | "REGULAR" | The Recipe Name to assign to the slot. Recipe must be present on machine. |

## Data Requirements / Validations

### Serial Numbers

- Serial Numbers must be valid and registered in BUNNlink / BUNNcloud
- Serial Numbers must be registered the the user account making the request

### Assignments

- Recipes assigned must match pre-configured Recipe aliases on the machine.
- Hoppers assigned must match pre-configured Hoppers aliases on the machine.
- Products assigned must match pre-configured Product aliases on the machine.
- Brew Schedules assigned must match pre-configured Schedule Labels on the machine.

## Example

```
{
  "externalId": "<your-id-for-this-assignment>",
  "assignments": [
    {
      "serialNumber": "SN1234",
      "reservoirs": [
        {
          "identifier": 1,
          "recipeName": "REGULAR",
          "scheduleLabel": "StandardSchedule"
        },
        {
          "identifier": 2,
          "recipeName": "DECAF",
          "scheduleLabel": "StandardSchedule"
        },
        {
          "identifier": 3,
          "recipeName": "PUMPKIN SPICE",
          "scheduleLabel": "PromotionalSchedule"
        }
      ]
    }
  ]
}
```
