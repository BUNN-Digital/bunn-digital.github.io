---
title: "Inlet Tank Over Temp"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Inlet Tank Over Temp

## Type:

E

## Category:

machine.telemetry

## Description: 

Inlet Tank Over Temp (8000.11076)

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
    "dateTime": "2023-06-12T13:10:31.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Inlet Tank Over Temp",
  "id": "88e0679e-f0b4-40da-a6d1-33cc4780e024",
  "category": "machine.telemetry",
  "type": "E"
}
```
