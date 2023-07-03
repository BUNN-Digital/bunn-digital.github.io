---
layout: page
title: "Tap Display Interface No Connection - Subsystem 1"
---

# Tap Display Interface No Connection - Subsystem 1

## Type:

E

## Category:

machine.telemetry

## Description: 

Tap Display Interface No Connection - Subsystem 1 (8000.11322)

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
    "dateTime": "2023-06-12T13:11:22.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Tap Display Interface No Connection - Subsystem 1",
  "id": "4025acba-8305-4f7b-ac79-9e3fe208aaf7",
  "category": "machine.telemetry",
  "type": "E"
}
```
