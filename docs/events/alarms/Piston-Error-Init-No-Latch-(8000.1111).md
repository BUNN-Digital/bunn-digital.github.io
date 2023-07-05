---
title: "Piston Error Init No Latch"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Piston Error Init No Latch

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Init No Latch (8000.1111)

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
    "dateTime": "2023-06-12T13:10:57.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Init No Latch",
  "id": "b9cd841f-fd56-40c2-a4ec-4e02ad4ada85",
  "category": "machine.telemetry",
  "type": "E"
}
```
