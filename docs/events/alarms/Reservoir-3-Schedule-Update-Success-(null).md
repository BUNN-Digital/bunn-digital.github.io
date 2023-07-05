---
layout: minimal
title: "Reservoir 3 Schedule Update Success"
---

# Reservoir 3 Schedule Update Success

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 3 Schedule Update Success (null)

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
    "dateTime": "2023-06-12T13:11:40.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 3 Schedule Update Success",
  "id": "256ea01b-764e-4bf7-8c01-4d411fa66939",
  "category": "machine.telemetry",
  "type": "E"
}
```
