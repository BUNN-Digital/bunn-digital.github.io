---
title: "Preheat Tank Sensor Short"
layout: minimal
parent: Alarms
---

# Preheat Tank Sensor Short

## Type:

E

## Category:

machine.telemetry

## Description: 

Preheat Tank Sensor Short (8000.11066)

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
    "dateTime": "2023-06-12T13:10:25.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Preheat Tank Sensor Short",
  "id": "44e0eff1-2496-4ab8-9f58-83570ffc062e",
  "category": "machine.telemetry",
  "type": "E"
}
```
