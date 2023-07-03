---
layout: page
title: "Reservoir Control Board Initialization"
---

# Reservoir Control Board Initialization

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir Control Board Initialization (8002.233)

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
    "dateTime": "2023-06-12T13:11:33.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir Control Board Initialization",
  "id": "863639a0-e2be-45a2-880f-c1b075e01863",
  "category": "machine.telemetry",
  "type": "E"
}
```
