---
title: "Left Grinder Overcurrent Shutdown"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Left Grinder Overcurrent Shutdown

## Type:

E

## Category:

machine.telemetry

## Description: 

Left Grinder Overcurrent Shutdown (8000.1103)

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
    "dateTime": "2023-06-12T13:10:13.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Left Grinder Overcurrent Shutdown",
  "id": "b4972088-07c9-406f-a9cc-6bd19f839e7f",
  "category": "machine.telemetry",
  "type": "E"
}
```
