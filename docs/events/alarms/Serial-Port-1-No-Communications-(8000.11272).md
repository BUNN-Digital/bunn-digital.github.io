---
title: "Serial Port 1 No Communications"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Serial Port 1 No Communications

## Type:

E

## Category:

machine.telemetry

## Description: 

Serial Port 1 No Communications (8000.11272)

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
    "dateTime": "2023-06-12T13:11:09.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Serial Port 1 No Communications",
  "id": "6eefa6a6-7f36-4763-a99c-f77e32159e01",
  "category": "machine.telemetry",
  "type": "E"
}
```
