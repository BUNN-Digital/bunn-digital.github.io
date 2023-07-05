---
layout: minimal
title: "Drip Tray Removed"
---

# Drip Tray Removed

## Type:

E

## Category:

machine.telemetry

## Description: 

Drip Tray Removed (8002.82)

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
    "dateTime": "2023-06-12T13:12:41.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Drip Tray Removed",
  "id": "347f3057-5943-4dea-bee5-d759b5cc9c9b",
  "category": "machine.telemetry",
  "type": "E"
}
```
