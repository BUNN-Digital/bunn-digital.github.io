---
title: "Recipe Brewed"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Recipe Brewed

## Type:

recipe.brewed

## Category:

machine.telemetry

## Description: 

Recipe Brewed (recipe.brewed)

## Payload:

```
[
  null,
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  },
  {
    "fieldName": "datapointId",
    "type": "text",
    "descrtiption": "Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific.",
    "example": "68|E|8000.10000"
  }
]
```

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-07-10T21:06:14.000Z",
    "zone": "UTC"
  },
  "payload": {
    "recipeVolumeMilliliters": "739",
    "recipeSize": "5",
    "serialNumber": "TEST000001",
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
  },
  "description": "Recipe Brewed",
  "_id": "d94df28f-2a5d-4926-bfbe-c34ab079935a",
  "label": "Recipe Brewed",
  "eventType": "recipe.brewed",
  "category": "machine.telemetry",
  "type": "recipe.brewed"
}
```
