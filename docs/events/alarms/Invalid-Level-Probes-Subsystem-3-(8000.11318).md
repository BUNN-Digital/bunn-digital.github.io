---
title: "Invalid Level Probes - Subsystem 3"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Invalid Level Probes - Subsystem 3

## Type:

E

## Category:

machine.telemetry

## Description: 

Invalid Level Probes - Subsystem 3 (8000.11318)

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
    "dateTime": "2023-06-12T13:11:17.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Invalid Level Probes - Subsystem 3",
  "id": "2f28a48c-df3a-4562-a762-b3b245a74ca5",
  "category": "machine.telemetry",
  "type": "E"
}
```
