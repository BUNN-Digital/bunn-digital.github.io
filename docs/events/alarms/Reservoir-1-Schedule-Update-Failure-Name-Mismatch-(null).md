---
layout: page
title: "Reservoir 1 Schedule Update Failure - Name Mismatch"
---

# Reservoir 1 Schedule Update Failure - Name Mismatch

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 1 Schedule Update Failure - Name Mismatch (null)

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
  "description": "Reservoir 1 Schedule Update Failure - Name Mismatch",
  "id": "b2de6035-f69d-435b-ba2c-1282e73d23eb",
  "category": "machine.telemetry",
  "type": "E"
}
```
