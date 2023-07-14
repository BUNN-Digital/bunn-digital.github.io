---
title: "Recipe Brewed"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Recipe Brewed

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

recipe.brewed

## Category:

machine.telemetry

## Description: 

Recipe Brewed (recipe.brewed)

## Payload Fields:

| Field | Type | Example | Description |
|:------|:-----|:--------|:------------|
| serialNumber | text | "SN1234" | The unique identifier for the machine that generated the event |
| datapointId | text | "68\|E\|8000.10000" | Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific. |

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "recipe.brewed",
  "description": "Recipe Brewed",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "recipeVolumeMilliliters": "739",
    "recipeSize": "5",
    "serialNumber": "SN1234",
    "timeForBrewWaitingToStartMilliseconds": "181974",
    "recipeNameInfo": "Test 814 Transform",
    "totalTimeOfBrewOnceStartedMilliseconds": "260452",
    "amountOfProductUsedInRecipeGrams": "31.7",
    "recipeHoldTemperatureCelcius": "86",
    "alternateAmountOfProductUsedInRecipeGrams": "0",
    "brewReason": "Box of Coffee",
    "recipeHoldVolumeMilliliters": "710",
    "datapointId": "68|D|814",
    "timestamp": "2023-04-06T14:05:58",
    "reservoirId": "1"
  }
}
```
