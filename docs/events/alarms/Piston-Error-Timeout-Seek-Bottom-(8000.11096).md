---
title: "Piston Error Timeout Seek Bottom"
layout: minimal
parent: Alarms
---

# Piston Error Timeout Seek Bottom

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Timeout Seek Bottom (8000.11096)

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
    "dateTime": "2023-06-12T13:10:45.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Timeout Seek Bottom",
  "id": "e6eb1403-814a-4f89-b147-747932cca8f1",
  "category": "machine.telemetry",
  "type": "E"
}
```
