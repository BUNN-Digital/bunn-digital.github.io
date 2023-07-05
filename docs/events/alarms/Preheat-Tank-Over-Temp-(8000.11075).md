---
layout: minimal
title: "Preheat Tank Over Temp"
parent: Alarms
---

# Preheat Tank Over Temp

## Type:

E

## Category:

machine.telemetry

## Description: 

Preheat Tank Over Temp (8000.11075)

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
    "dateTime": "2023-06-12T13:10:30.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Preheat Tank Over Temp",
  "id": "7270cb0a-b97c-486f-be3f-76ac0160502c",
  "category": "machine.telemetry",
  "type": "E"
}
```
