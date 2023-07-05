---
title: "Rinse Complete"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Rinse Complete

## Type:

E

## Category:

machine.telemetry

## Description: 

Rinse Complete (8002.254)

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
    "dateTime": "2023-06-12T13:11:49.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Rinse Complete",
  "id": "6a7ef452-528a-4763-a95c-0cbd95a7d350",
  "category": "machine.telemetry",
  "type": "E"
}
```
