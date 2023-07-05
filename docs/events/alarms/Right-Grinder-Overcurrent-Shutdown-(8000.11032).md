---
title: "Right Grinder Overcurrent Shutdown"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Right Grinder Overcurrent Shutdown

## Type:

E

## Category:

machine.telemetry

## Description: 

Right Grinder Overcurrent Shutdown (8000.11032)

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
    "dateTime": "2023-06-12T13:10:14.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Right Grinder Overcurrent Shutdown",
  "id": "1350c78c-1d93-42ca-8457-966fe15c7ee8",
  "category": "machine.telemetry",
  "type": "E"
}
```
