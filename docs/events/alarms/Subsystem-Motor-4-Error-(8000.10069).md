---
#layout: minimal
title: "Subsystem/Motor 4 Error"
---

# Subsystem/Motor 4 Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 4 Error (8000.10069)

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
    "dateTime": "2023-06-12T13:10:08.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Subsystem/Motor 4 Error",
  "id": "72f18982-17b9-45ca-b1b3-bc0955e07e1d",
  "category": "machine.telemetry",
  "type": "E"
}
```
