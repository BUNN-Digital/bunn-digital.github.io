---
layout: minimal
title: "Reservoir Control Board 2 Initialization"
---

# Reservoir Control Board 2 Initialization

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir Control Board 2 Initialization (8002.234)

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
    "dateTime": "2023-06-12T13:11:34.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir Control Board 2 Initialization",
  "id": "04e8355d-2f56-437f-bd7f-b465a3d65d76",
  "category": "machine.telemetry",
  "type": "E"
}
```
