---
title: "Recipe Drained"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Recipe Drained

## Type:

recipe.drained

## Category:

machine.telemetry

## Description: 

Recipe Drained (recipe.drained)

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
    "dateTime": "2023-07-10T21:06:22.000Z",
    "zone": "UTC"
  },
  "payload": {
    "recipeAgeAtTimeOfDrainMinutes": "91",
    "serialNumber": "TEST000001",
    "drainDurationMilliseconds": "38248",
    "recipeNameInfo": "Test 816 Transform",
    "drainReason": "Invalid",
    "recipeTemperatureCelcius": "84",
    "volumeDrainedMilliliters": "828",
    "datapointId": "68|D|816",
    "timestamp": "2023-04-12T19:48:15",
    "reservoirId": "3"
  },
  "description": "Recipe Drained",
  "_id": "a74d5ff2-64da-44c1-839f-2f9c14643131",
  "label": "Recipe Drained",
  "eventType": "recipe.drained",
  "category": "machine.telemetry",
  "type": "recipe.drained"
}
```
