---
title: "Operator Door Closed"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Operator Door Closed

## Type:

E

## Category:

machine.telemetry

## Description: 

Operator Door Closed (8002.63)

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
    "dateTime": "2023-06-12T13:12:24.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Operator Door Closed",
  "id": "95de2f61-ccb1-4002-b4e5-e05dea0e8aab",
  "category": "machine.telemetry",
  "type": "E"
}
```
