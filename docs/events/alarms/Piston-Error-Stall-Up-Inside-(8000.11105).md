---
layout: minimal
title: "Piston Error Stall Up Inside"
parent: Alarms
---

# Piston Error Stall Up Inside

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Up Inside (8000.11105)

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
    "dateTime": "2023-06-12T13:10:54.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Up Inside",
  "id": "4e763bad-0063-4362-80e2-e4f80d09a92a",
  "category": "machine.telemetry",
  "type": "E"
}
```
