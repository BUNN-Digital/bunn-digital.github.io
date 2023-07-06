---
title: "Reservoir Swing Arm Up"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Reservoir Swing Arm Up

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir Swing Arm Up (8002.235)

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
    "dateTime": "2023-06-12T13:11:35.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir Swing Arm Up",
  "id": "d8f660d9-2abb-4ba6-81e7-aca36d86677f",
  "category": "machine.telemetry",
  "type": "E"
}
```
