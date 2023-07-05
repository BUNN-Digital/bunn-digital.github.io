---
layout: minimal
title: "Left Hopper Missing"
parent: Alarms
---

# Left Hopper Missing

## Type:

E

## Category:

machine.telemetry

## Description: 

Left Hopper Missing (8002.67)

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
    "dateTime": "2023-06-12T13:12:26.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Left Hopper Missing",
  "id": "dabc0078-8d00-478e-993c-33341927dbe1",
  "category": "machine.telemetry",
  "type": "E"
}
```
