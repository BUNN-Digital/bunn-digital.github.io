---
title: "Reservoir Access Door Open"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Reservoir Access Door Open

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir Access Door Open (8002.231)

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
    "dateTime": "2023-06-12T13:11:32.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir Access Door Open",
  "id": "ae46cea4-d29a-442c-a84b-9adb758ef74c",
  "category": "machine.telemetry",
  "type": "E"
}
```
