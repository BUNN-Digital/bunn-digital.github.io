---
title: "Recipe Position Status - Non Portion Controlled"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Recipe Position Status - Non Portion Controlled

## Type:

recipe.tap.activated

## Category:

machine.telemetry

## Description: 

Recipe Position Status - Non Portion Controlled (recipe.tap.activated)

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
    "dateTime": "2023-07-10T21:06:35.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "recipeNameInfo": "Test 817 Transform",
    "datapointId": "68|D|817",
    "tapAvailability": "Not Available",
    "tapId": "2",
    "timestamp": "2023-04-12T18:26:16",
    "reservoirId": "2",
    "tapAvailabilityReason": "Unknown"
  },
  "description": "Recipe Position Status - Non Portion Controlled",
  "_id": "ce563a75-183b-4544-8fe6-76d0d96a22be",
  "label": "Recipe Position Status - Non Portion Controlled",
  "category": "machine.telemetry",
  "type": "recipe.tap.activated"
}
```
