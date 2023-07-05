---
title: "Piston Error Stall Up Latched"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Piston Error Stall Up Latched

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Up Latched (8000.11103)

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
    "dateTime": "2023-06-12T13:10:52.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Up Latched",
  "id": "3fd21a23-d3ca-4fb8-a65e-448a416ef58a",
  "category": "machine.telemetry",
  "type": "E"
}
```
