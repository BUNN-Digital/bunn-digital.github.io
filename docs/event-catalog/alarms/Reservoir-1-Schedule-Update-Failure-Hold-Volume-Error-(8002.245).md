---
title: "Reservoir 1 Schedule Update Failure - Hold Volume Error"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Reservoir 1 Schedule Update Failure - Hold Volume Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 1 Schedule Update Failure - Hold Volume Error (8002.245)

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
    "dateTime": "2023-06-12T13:11:43.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 1 Schedule Update Failure - Hold Volume Error",
  "id": "905bf0c0-da0d-4b6b-9c20-6caaa9388a0c",
  "category": "machine.telemetry",
  "type": "E"
}
```
