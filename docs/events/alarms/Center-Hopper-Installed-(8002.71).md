---
layout: minimal
title: "Center Hopper Installed"
---

# Center Hopper Installed

## Type:

E

## Category:

machine.telemetry

## Description: 

Center Hopper Installed (8002.71)

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
    "dateTime": "2023-06-12T13:12:32.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Center Hopper Installed",
  "id": "2306848c-9567-4a10-b713-8b807e2dbfc8",
  "category": "machine.telemetry",
  "type": "E"
}
```
