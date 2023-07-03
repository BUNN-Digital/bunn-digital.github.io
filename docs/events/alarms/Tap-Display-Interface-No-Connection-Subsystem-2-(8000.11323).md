---
#layout: minimal
title: "Tap Display Interface No Connection - Subsystem 2"
---

# Tap Display Interface No Connection - Subsystem 2

## Type:

E

## Category:

machine.telemetry

## Description: 

Tap Display Interface No Connection - Subsystem 2 (8000.11323)

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
    "dateTime": "2023-06-12T13:11:23.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Tap Display Interface No Connection - Subsystem 2",
  "id": "f0f7082e-5fbf-410a-b518-1a9dc4c2026e",
  "category": "machine.telemetry",
  "type": "E"
}
```
