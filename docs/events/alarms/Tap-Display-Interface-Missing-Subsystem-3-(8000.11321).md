---
layout: page
title: "Tap Display Interface Missing - Subsystem 3"
---

# Tap Display Interface Missing - Subsystem 3

## Type:

E

## Category:

machine.telemetry

## Description: 

Tap Display Interface Missing - Subsystem 3 (8000.11321)

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
    "dateTime": "2023-06-12T13:11:21.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Tap Display Interface Missing - Subsystem 3",
  "id": "bf583adb-9ff2-4f7e-8988-0d96fce1de44",
  "category": "machine.telemetry",
  "type": "E"
}
```
