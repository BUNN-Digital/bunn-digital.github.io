---
title: "Finish Tank Heat Too Long"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Finish Tank Heat Too Long

## Type:

E

## Category:

machine.telemetry

## Description: 

Finish Tank Heat Too Long (8000.11068)

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
    "dateTime": "2023-06-12T13:10:26.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Finish Tank Heat Too Long",
  "id": "17b0b764-087b-4ddb-b2d8-896f7b2c5897",
  "category": "machine.telemetry",
  "type": "E"
}
```