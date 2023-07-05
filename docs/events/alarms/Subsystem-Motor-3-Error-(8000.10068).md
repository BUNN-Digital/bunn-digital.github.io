---
title: "Subsystem/Motor 3 Error"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Subsystem/Motor 3 Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 3 Error (8000.10068)

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
    "dateTime": "2023-06-12T13:10:07.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Subsystem/Motor 3 Error",
  "id": "4d91bf5b-2ff3-4b57-bdaf-2dffa810c949",
  "category": "machine.telemetry",
  "type": "E"
}
```
