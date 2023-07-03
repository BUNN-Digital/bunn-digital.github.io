---
#layout: minimal
title: "Piston Error Stall Up Outside"
---

# Piston Error Stall Up Outside

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Up Outside (8000.11107)

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
    "dateTime": "2023-06-12T13:10:55.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Up Outside",
  "id": "6303c79e-659f-4237-8c63-5f55f47157f0",
  "category": "machine.telemetry",
  "type": "E"
}
```
