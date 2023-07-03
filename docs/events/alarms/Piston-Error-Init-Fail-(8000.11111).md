---
#layout: minimal
title: "Piston Error Init Fail"
---

# Piston Error Init Fail

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Init Fail (8000.11111)

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
    "dateTime": "2023-06-12T13:10:59.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Init Fail",
  "id": "c0041508-d765-4d35-82f0-becc159d404e",
  "category": "machine.telemetry",
  "type": "E"
}
```
