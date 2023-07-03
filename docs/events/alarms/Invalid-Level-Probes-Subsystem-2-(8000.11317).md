---
layout: page
title: "Invalid Level Probes - Subsystem 2"
---

# Invalid Level Probes - Subsystem 2

## Type:

E

## Category:

machine.telemetry

## Description: 

Invalid Level Probes - Subsystem 2 (8000.11317)

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
    "dateTime": "2023-06-12T13:11:16.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Invalid Level Probes - Subsystem 2",
  "id": "d206bbff-d199-4cf8-ac35-314824c400a2",
  "category": "machine.telemetry",
  "type": "E"
}
```