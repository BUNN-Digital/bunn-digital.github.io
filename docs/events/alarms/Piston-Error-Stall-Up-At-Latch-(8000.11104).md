---
layout: minimal
title: "Piston Error Stall Up At Latch"
---

# Piston Error Stall Up At Latch

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Up At Latch (8000.11104)

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
    "dateTime": "2023-06-12T13:10:53.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Up At Latch",
  "id": "a6125d54-a8a6-4d8b-97d4-3d3882c5cc22",
  "category": "machine.telemetry",
  "type": "E"
}
```
