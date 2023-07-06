---
title: "Preheat Tank Heat Too Long"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Preheat Tank Heat Too Long

## Type:

E

## Category:

machine.telemetry

## Description: 

Preheat Tank Heat Too Long (8000.11069)

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
    "dateTime": "2023-06-12T13:10:26.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Preheat Tank Heat Too Long",
  "id": "8abaa6b5-44ae-4e8d-9a67-ee2a83d577b7",
  "category": "machine.telemetry",
  "type": "E"
}
```
