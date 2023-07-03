---
layout: page
title: "Brew Error Piston Move Timeout"
---

# Brew Error Piston Move Timeout

## Type:

E

## Category:

machine.telemetry

## Description: 

Brew Error Piston Move Timeout (8000.11086)

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
    "dateTime": "2023-06-12T13:10:36.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Brew Error Piston Move Timeout",
  "id": "2cc7f165-2df8-4d50-8cc3-fa71c551b8f8",
  "category": "machine.telemetry",
  "type": "E"
}
```
