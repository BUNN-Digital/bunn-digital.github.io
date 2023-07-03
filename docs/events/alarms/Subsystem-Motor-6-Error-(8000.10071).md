---
layout: page
title: "Subsystem/Motor 6 Error"
---

# Subsystem/Motor 6 Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 6 Error (8000.10071)

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
    "dateTime": "2023-06-12T13:10:10.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Subsystem/Motor 6 Error",
  "id": "1600a548-a252-4ab1-80d1-4fa59301667d",
  "category": "machine.telemetry",
  "type": "E"
}
```