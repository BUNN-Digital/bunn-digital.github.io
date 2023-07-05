---
layout: minimal
title: "Right Hopper Installed"
parent: Alarms
---

# Right Hopper Installed

## Type:

E

## Category:

machine.telemetry

## Description: 

Right Hopper Installed (8002.69)

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
    "dateTime": "2023-06-12T13:12:30.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Right Hopper Installed",
  "id": "59de43e3-0082-47a6-a552-af029a4a6b00",
  "category": "machine.telemetry",
  "type": "E"
}
```
