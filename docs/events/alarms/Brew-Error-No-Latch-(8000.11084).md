---
layout: minimal
title: "Brew Error No Latch"
---

# Brew Error No Latch

## Type:

E

## Category:

machine.telemetry

## Description: 

Brew Error No Latch (8000.11084)

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
    "dateTime": "2023-06-12T13:10:35.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Brew Error No Latch",
  "id": "fe217368-320e-43e2-89b0-19866c1d7b27",
  "category": "machine.telemetry",
  "type": "E"
}
```
