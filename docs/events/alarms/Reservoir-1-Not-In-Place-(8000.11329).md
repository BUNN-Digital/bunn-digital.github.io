---
layout: page
title: "Reservoir 1 Not In Place"
---

# Reservoir 1 Not In Place

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 1 Not In Place (8000.11329)

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
    "dateTime": "2023-06-12T13:11:28.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 1 Not In Place",
  "id": "ae498e12-b5c0-40ea-bf7c-ecbd9b27b2a8",
  "category": "machine.telemetry",
  "type": "E"
}
```