---
title: "Free Vend"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Free Vend

## Type:

E

## Category:

machine.telemetry

## Description: 

Free Vend (8002.27)

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
    "dateTime": "2023-06-12T13:11:54.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Free Vend",
  "id": "f758ae37-24ed-4138-9a9d-11fe9d98a0de",
  "category": "machine.telemetry",
  "type": "E"
}
```
