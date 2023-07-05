---
layout: minimal
title: "Brew Error No Swipe"
---

# Brew Error No Swipe

## Type:

E

## Category:

machine.telemetry

## Description: 

Brew Error No Swipe (8000.11089)

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
    "dateTime": "2023-06-12T13:10:40.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Brew Error No Swipe",
  "id": "6fcebe37-7d86-4fb7-be9d-71e944675e39",
  "category": "machine.telemetry",
  "type": "E"
}
```
