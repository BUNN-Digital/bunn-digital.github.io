---
title: "Right Hopper Missing"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Right Hopper Missing

## Type:

E

## Category:

machine.telemetry

## Description: 

Right Hopper Missing (8002.66)

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
    "dateTime": "2023-06-12T13:12:26.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Right Hopper Missing",
  "id": "a89a795c-5627-42f3-8171-72f9fd874d2d",
  "category": "machine.telemetry",
  "type": "E"
}
```
