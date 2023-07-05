---
layout: minimal
title: "Piston Error Timeout Locating"
parent: Alarms
---

# Piston Error Timeout Locating

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Timeout Locating (8000.11097)

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
    "dateTime": "2023-06-12T13:10:46.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Timeout Locating",
  "id": "fa90c48e-6cd5-4829-b063-a7f57f8a2b35",
  "category": "machine.telemetry",
  "type": "E"
}
```
