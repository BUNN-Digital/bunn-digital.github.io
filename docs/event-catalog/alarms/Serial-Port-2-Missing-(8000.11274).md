---
title: "Serial Port 2 Missing"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Serial Port 2 Missing

## Type:

E

## Category:

machine.telemetry

## Description: 

Serial Port 2 Missing (8000.11274)

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
    "dateTime": "2023-06-12T13:11:11.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Serial Port 2 Missing",
  "id": "bfd3b6d0-b4c4-4385-8321-eb40d9e8abc9",
  "category": "machine.telemetry",
  "type": "E"
}
```