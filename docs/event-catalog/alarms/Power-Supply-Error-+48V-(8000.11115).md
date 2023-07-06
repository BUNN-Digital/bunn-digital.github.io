---
title: "Power Supply Error +48V"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Power Supply Error +48V

## Type:

E

## Category:

machine.telemetry

## Description: 

Power Supply Error +48V (8000.11115)

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
    "dateTime": "2023-06-12T13:11:03.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Power Supply Error +48V",
  "id": "62d92848-bd34-492f-9f59-d94737a0b6f5",
  "category": "machine.telemetry",
  "type": "E"
}
```
