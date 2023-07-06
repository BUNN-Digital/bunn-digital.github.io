---
title: "Mode Is In Standby"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Mode Is In Standby

## Type:

E

## Category:

machine.telemetry

## Description: 

Mode Is In Standby (8000.11327)

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
    "dateTime": "2023-06-12T13:11:26.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Mode Is In Standby",
  "id": "2ef09fc0-0b32-4255-8990-e812d32c42fa",
  "category": "machine.telemetry",
  "type": "E"
}
```
