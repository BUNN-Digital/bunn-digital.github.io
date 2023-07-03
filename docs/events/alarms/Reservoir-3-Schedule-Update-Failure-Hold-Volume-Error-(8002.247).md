---
#layout: minimal
title: "Reservoir 3 Schedule Update Failure - Hold Volume Error"
---

# Reservoir 3 Schedule Update Failure - Hold Volume Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 3 Schedule Update Failure - Hold Volume Error (8002.247)

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
    "dateTime": "2023-06-12T13:11:44.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 3 Schedule Update Failure - Hold Volume Error",
  "id": "d6d0e09b-ef2f-4c66-8d9b-111b6795f9cf",
  "category": "machine.telemetry",
  "type": "E"
}
```
