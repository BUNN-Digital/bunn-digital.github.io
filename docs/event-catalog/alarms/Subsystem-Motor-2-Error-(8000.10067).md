---
title: "Subsystem/Motor 2 Error"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Subsystem/Motor 2 Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 2 Error (8000.10067)

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
    "dateTime": "2023-06-12T13:10:06.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Subsystem/Motor 2 Error",
  "id": "7a2ed5cb-6f7b-459c-9c2d-070174dadf83",
  "category": "machine.telemetry",
  "type": "E"
}
```
