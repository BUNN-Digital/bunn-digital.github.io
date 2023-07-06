---
title: "Preheat Tank Sensor Open"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Preheat Tank Sensor Open

## Type:

E

## Category:

machine.telemetry

## Description: 

Preheat Tank Sensor Open (8000.11063)

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
    "dateTime": "2023-06-12T13:10:22.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Preheat Tank Sensor Open",
  "id": "340a2646-8325-4a66-979f-35da1644a294",
  "category": "machine.telemetry",
  "type": "E"
}
```
