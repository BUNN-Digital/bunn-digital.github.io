---
#layout: minimal
title: "Check Valve Not Opening - Subsystem 1"
---

# Check Valve Not Opening - Subsystem 1

## Type:

E

## Category:

machine.telemetry

## Description: 

Check Valve Not Opening - Subsystem 1 (8000.11313)

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
    "dateTime": "2023-06-12T13:11:13.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Check Valve Not Opening - Subsystem 1",
  "id": "ec113251-a1c3-4995-8301-273a3e232651",
  "category": "machine.telemetry",
  "type": "E"
}
```
