---
title: "Cleaning Required Subsystem - Hot Coffee"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Cleaning Required Subsystem - Hot Coffee

## Type:

E

## Category:

machine.telemetry

## Description: 

Cleaning Required Subsystem - Hot Coffee (8000.1116)

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
    "dateTime": "2023-06-12T13:11:05.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Cleaning Required Subsystem - Hot Coffee",
  "id": "438d1e31-4488-498d-8fe0-e41f83eb1118",
  "category": "machine.telemetry",
  "type": "E"
}
```
