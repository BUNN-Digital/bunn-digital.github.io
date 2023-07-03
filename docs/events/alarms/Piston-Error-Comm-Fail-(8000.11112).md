---
#layout: minimal
title: "Piston Error Comm Fail"
---

# Piston Error Comm Fail

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Comm Fail (8000.11112)

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
    "dateTime": "2023-06-12T13:11:00.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Comm Fail",
  "id": "551a32c6-d26e-436c-8cf5-f34577fb8888",
  "category": "machine.telemetry",
  "type": "E"
}
```
