---
title: "Center Grinder Overcurrent Shutdown"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Center Grinder Overcurrent Shutdown

## Type:

E

## Category:

machine.telemetry

## Description: 

Center Grinder Overcurrent Shutdown (8000.11043)

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
    "dateTime": "2023-06-12T13:10:18.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Center Grinder Overcurrent Shutdown",
  "id": "4e58e314-7e61-472f-857f-f8489ef5bb64",
  "category": "machine.telemetry",
  "type": "E"
}
```
