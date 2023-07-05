---
title: "Recipe Drained"
layout: minimal
parent: Alarms
---

# Recipe Drained

## Type:

DrainEvent

## Category:

machine.telemetry

## Description: 

Recipe Drained (null)

## Payload:

```
[
  null,
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  }
]
```

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-06-12T15:42:18.000Z",
    "zone": "UTC"
  },
  "payload": {
    "recipeAgeAtTimeOfDrainMinutes": "91",
    "serialNumber": "TEST000001",
    "drainDurationMilliseconds": "38248",
    "recipeNameInfo": "JR Automated Test 816",
    "drainReason": "Old Coffee",
    "recipeTemperatureCelcius": "84",
    "volumeDrainedMilliliters": "828",
    "timestamp": "2023-04-12T19:48:15",
    "reservoirId": "3"
  },
  "description": "Recipe Drained",
  "id": "d6120c81-254a-4733-995b-86726d820848",
  "category": "machine.telemetry",
  "type": "DrainEvent"
}
```
