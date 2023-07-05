---
title: "System API Event"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# System API Event

## Type:

E

## Category:

machine.telemetry

## Description: 

System API Event (null)

## Payload:

```
[
  null,
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
    "dateTime": "2023-06-12T13:12:50.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "decimal": "75"
  },
  "description": "System API Event",
  "id": "b742827c-243a-4fa1-8c3b-890395166ad9",
  "category": "machine.telemetry",
  "type": "E"
}
```
