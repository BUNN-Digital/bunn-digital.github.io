---
title: "Check Valve Not Opening - Subsystem 3"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Check Valve Not Opening - Subsystem 3

## Type:

E

## Category:

machine.telemetry

## Description: 

Check Valve Not Opening - Subsystem 3 (8000.11315)

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
    "dateTime": "2023-06-12T13:11:15.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Check Valve Not Opening - Subsystem 3",
  "id": "6b866d10-6dc6-4595-9ba9-59f2a3cdd466",
  "category": "machine.telemetry",
  "type": "E"
}
```
