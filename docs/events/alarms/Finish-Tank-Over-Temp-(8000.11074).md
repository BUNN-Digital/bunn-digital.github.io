---
layout: minimal
title: "Finish Tank Over Temp"
---

# Finish Tank Over Temp

## Type:

E

## Category:

machine.telemetry

## Description: 

Finish Tank Over Temp (8000.11074)

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
    "dateTime": "2023-06-12T13:10:29.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Finish Tank Over Temp",
  "id": "5cdac044-88b7-47a3-a179-a13acec0d67d",
  "category": "machine.telemetry",
  "type": "E"
}
```
