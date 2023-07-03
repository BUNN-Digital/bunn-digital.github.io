---
layout: page
title: "Brew Error Piston Not Ready"
---

# Brew Error Piston Not Ready

## Type:

E

## Category:

machine.telemetry

## Description: 

Brew Error Piston Not Ready (8000.11091)

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
    "dateTime": "2023-06-12T13:10:41.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Brew Error Piston Not Ready",
  "id": "dab04230-40ed-4d21-9c3f-f67f3c949cfc",
  "category": "machine.telemetry",
  "type": "E"
}
```
