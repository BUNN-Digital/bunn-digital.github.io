---
title: "Piston Error Home Not Open"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Piston Error Home Not Open

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Home Not Open (8000.11093)

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
    "dateTime": "2023-06-12T13:10:43.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Home Not Open",
  "id": "78597668-8b59-4a81-9b4c-7f4b9e1a7648",
  "category": "machine.telemetry",
  "type": "E"
}
```
