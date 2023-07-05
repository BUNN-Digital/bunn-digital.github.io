---
title: "Serial Port 1 Missing"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Serial Port 1 Missing

## Type:

E

## Category:

machine.telemetry

## Description: 

Serial Port 1 Missing (8000.11271)

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
    "dateTime": "2023-06-12T13:11:08.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Serial Port 1 Missing",
  "id": "9d5371ea-f90f-4c10-9ede-22b7dd23eb3d",
  "category": "machine.telemetry",
  "type": "E"
}
```
