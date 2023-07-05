---
layout: minimal
title: "Circuit Over Temperature Error"
---

# Circuit Over Temperature Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Circuit Over Temperature Error (8000.10023)

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
    "dateTime": "2023-06-12T13:10:03.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Circuit Over Temperature Error",
  "id": "25750662-d200-4d60-85a0-eab71a4360ec",
  "category": "machine.telemetry",
  "type": "E"
}
```
