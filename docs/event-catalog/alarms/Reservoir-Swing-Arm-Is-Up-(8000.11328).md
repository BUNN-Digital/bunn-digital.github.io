---
title: "Reservoir Swing Arm Is Up"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Reservoir Swing Arm Is Up

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir Swing Arm Is Up (8000.11328)

## Payload:

```
[
  {
    "fieldName": "boolean",
    "type": "boolean",
    "descrtiption": "An unspecified boolean value - awaiting more specific definition. Most commonly this describes the state of the event itself - e.g. active (true) or inactive/resolved (false) if the event is an alarm",
    "example": "true"
  },
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
    "dateTime": "2023-06-12T13:11:26.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir Swing Arm Is Up",
  "id": "6759ccfb-adc6-479b-9766-514ffab88b77",
  "category": "machine.telemetry",
  "type": "E"
}
```
