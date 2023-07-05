---
title: "Center Hopper Missing"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Center Hopper Missing

## Type:

E

## Category:

machine.telemetry

## Description: 

Center Hopper Missing (8002.68)

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
    "dateTime": "2023-06-12T13:12:29.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Center Hopper Missing",
  "id": "e580611b-f2da-438a-b62e-826cb2ee69a0",
  "category": "machine.telemetry",
  "type": "E"
}
```
