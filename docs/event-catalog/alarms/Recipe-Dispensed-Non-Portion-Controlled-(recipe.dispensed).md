---
title: "Recipe Dispensed - Non Portion Controlled"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Recipe Dispensed - Non Portion Controlled

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

recipe.dispensed

## Category:

machine.telemetry

## Description: 

Recipe Dispensed - Non Portion Controlled (recipe.dispensed)

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "recipe.dispensed",
  "description": "Recipe Dispensed - Non Portion Controlled",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "volumeDispensedMilliliters": "0",
    "serialNumber": "SN1234",
    "recipeNameInfo": "Test 815 Transform",
    "recipeTemperatureCelcius": "84",
    "recipeAgeAtTimeOfDispenseMinutes": "65535",
    "datapointId": "68|D|815",
    "tapAvailability": "Available",
    "tapId": "1",
    "tapActiveDurationMilliseconds": "2218",
    "timestamp": "2023-01-25T14:12:45",
    "reservoirId": "1"
  }
}
```

## Payload Description

```
[
  null,
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "SN1234"
  },
  {
    "fieldName": "datapointId",
    "type": "text",
    "descrtiption": "Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific.",
    "example": "68|E|8000.10000"
  }
]
```

