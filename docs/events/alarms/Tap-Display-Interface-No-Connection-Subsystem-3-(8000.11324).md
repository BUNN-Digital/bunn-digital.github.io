---
title: "Tap Display Interface No Connection - Subsystem 3"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Tap Display Interface No Connection - Subsystem 3

## Type:

E

## Category:

machine.telemetry

## Description: 

Tap Display Interface No Connection - Subsystem 3 (8000.11324)

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
    "dateTime": "2023-06-12T13:11:24.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Tap Display Interface No Connection - Subsystem 3",
  "id": "053bedbc-cf22-4d9f-ac8e-936b016637be",
  "category": "machine.telemetry",
  "type": "E"
}
```
