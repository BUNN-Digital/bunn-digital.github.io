---
title: "Recipe Dispensed - Non Portion Controlled"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Recipe Dispensed - Non Portion Controlled

## Type:

DispenseEvent

## Category:

machine.telemetry

## Description: 

Recipe Dispensed - Non Portion Controlled (null)

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
    "dateTime": "2023-06-12T15:41:48.000Z",
    "zone": "UTC"
  },
  "payload": {
    "volumeDispensedMilliliters": "0",
    "serialNumber": "TEST000001",
    "recipeNameInfo": "JR Automated Test 815",
    "recipeTemperatureCelcius": "84",
    "recipeAgeAtTimeOfDispenseMinutes": "65535",
    "tapAvailability": "Not Available",
    "tapId": "1",
    "tapActiveDurationMilliseconds": "2218",
    "timestamp": "2023-01-25T14:12:45",
    "reservoirId": "1"
  },
  "description": "Recipe Dispensed - Non Portion Controlled",
  "id": "d2e6d094-027a-4fca-9fab-ce39fb77e471",
  "category": "machine.telemetry",
  "type": "DispenseEvent"
}
```
