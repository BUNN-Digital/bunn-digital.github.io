---
title: "Power Up"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Power Up

## Type:

E

## Category:

machine.telemetry

## Description: 

Power Up (8002.1)

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
    "dateTime": "2023-06-12T13:11:31.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Power Up",
  "id": "8c8940ed-0daa-473d-948c-668fbacb3bd9",
  "category": "machine.telemetry",
  "type": "E"
}
```
