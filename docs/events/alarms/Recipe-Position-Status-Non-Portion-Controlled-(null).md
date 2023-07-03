---
#layout: minimal
title: "Recipe Position Status - Non Portion Controlled"
---

# Recipe Position Status - Non Portion Controlled

## Type:

recipe.tap.activated

## Category:

machine.telemetry

## Description: 

Recipe Position Status - Non Portion Controlled (null)

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
    "dateTime": "2023-06-12T13:09:55.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "recipeNameInfo": "JR Automated Test 817",
    "tapAvailability": "Not Available",
    "tapId": "2",
    "timestamp": "2023-04-12T18:26:16",
    "reservoirId": "2",
    "tapAvailabilityReason": "Unknown"
  },
  "description": "Recipe Position Status - Non Portion Controlled",
  "id": "2d80b9f1-33b3-41e8-aa51-f432e47282a1",
  "category": "machine.telemetry",
  "type": "recipe.tap.activated"
}
```
