---
title: "Reservoir 2 Not In Place"
layout: minimal
parent: Alarms
---

# Reservoir 2 Not In Place

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 2 Not In Place (8000.1133)

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
    "dateTime": "2023-06-12T13:11:30.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 2 Not In Place",
  "id": "a663e2e7-c898-4b76-8aeb-63d764ba6664",
  "category": "machine.telemetry",
  "type": "E"
}
```
