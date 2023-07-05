---
layout: minimal
title: "Right Grinder No Current Shutdown"
---

# Right Grinder No Current Shutdown

## Type:

E

## Category:

machine.telemetry

## Description: 

Right Grinder No Current Shutdown (8000.11033)

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
    "dateTime": "2023-06-12T13:10:15.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Right Grinder No Current Shutdown",
  "id": "939f2d2f-d441-4e6f-a529-00b61de7ea19",
  "category": "machine.telemetry",
  "type": "E"
}
```
