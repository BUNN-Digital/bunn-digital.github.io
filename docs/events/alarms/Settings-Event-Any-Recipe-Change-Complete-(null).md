---
layout: page
title: "Settings Event - Any Recipe Change Complete"
---

# Settings Event - Any Recipe Change Complete

## Type:

E

## Category:

machine.telemetry

## Description: 

Settings Event - Any Recipe Change Complete (null)

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
    "dateTime": "2023-06-12T13:12:46.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Settings Event - Any Recipe Change Complete",
  "id": "61cc4057-da28-4fde-ba12-240ea716931b",
  "category": "machine.telemetry",
  "type": "E"
}
```
