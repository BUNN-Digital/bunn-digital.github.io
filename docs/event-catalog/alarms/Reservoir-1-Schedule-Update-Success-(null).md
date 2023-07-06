---
title: "Reservoir 1 Schedule Update Success"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Reservoir 1 Schedule Update Success

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 1 Schedule Update Success (null)

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
    "dateTime": "2023-06-12T13:11:37.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 1 Schedule Update Success",
  "id": "d8a8f88e-974c-4044-a268-dc83619ceece",
  "category": "machine.telemetry",
  "type": "E"
}
```
