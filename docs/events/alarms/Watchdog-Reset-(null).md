---
layout: minimal
title: "Watchdog Reset"
---

# Watchdog Reset

## Type:

E

## Category:

machine.telemetry

## Description: 

Watchdog Reset (null)

## Payload:

```
[
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  },
  {
    "fieldName": "text",
    "type": "text",
    "descrtiption": "Unspecified text value - awaiting more specific definition.",
    "example": "This is a text value."
  }
]
```

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-06-12T13:12:14.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Watchdog Reset",
  "id": "3af38800-19ff-424d-80eb-4b0e67177a44",
  "category": "machine.telemetry",
  "type": "E"
}
```
