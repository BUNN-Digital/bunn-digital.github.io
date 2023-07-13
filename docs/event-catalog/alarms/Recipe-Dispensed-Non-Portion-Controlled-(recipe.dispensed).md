---
title: "Recipe Dispensed - Non Portion Controlled"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Recipe Dispensed - Non Portion Controlled

## Type:

recipe.dispensed

## Category:

machine.telemetry

## Description: 

Recipe Dispensed - Non Portion Controlled (recipe.dispensed)

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
    "dateTime": "2023-07-10T21:06:15.000Z",
    "zone": "UTC"
  },
  "payload": {
    "volumeDispensedMilliliters": "0",
    "serialNumber": "TEST000001",
    "recipeNameInfo": "Test 815 Transform",
    "recipeTemperatureCelcius": "84",
    "recipeAgeAtTimeOfDispenseMinutes": "65535",
    "datapointId": "68|D|815",
    "tapAvailability": "Available",
    "tapId": "1",
    "tapActiveDurationMilliseconds": "2218",
    "timestamp": "2023-01-25T14:12:45",
    "reservoirId": "1"
  },
  "description": "Recipe Dispensed - Non Portion Controlled",
  "_id": "7024bb9a-0b4b-4455-8c7e-165fdc5ad1fb",
  "label": "Recipe Dispensed - Non Portion Controlled",
  "category": "machine.telemetry",
  "type": "recipe.dispensed"
}
```
