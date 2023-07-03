---
layout: page
title: "Piston Error Stall Down Outside"
---

# Piston Error Stall Down Outside

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Down Outside (8000.11099)

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
    "dateTime": "2023-06-12T13:10:49.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Down Outside",
  "id": "08f6024b-ba90-4037-8ef7-e11d05f9dbc5",
  "category": "machine.telemetry",
  "type": "E"
}
```