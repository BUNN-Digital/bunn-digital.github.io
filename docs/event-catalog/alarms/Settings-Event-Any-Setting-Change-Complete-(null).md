---
title: "Settings Event - Any Setting Change Complete"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Settings Event - Any Setting Change Complete

## Type:

E

## Category:

machine.telemetry

## Description: 

Settings Event - Any Setting Change Complete (null)

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
    "dateTime": "2023-06-12T13:12:45.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Settings Event - Any Setting Change Complete",
  "id": "02490b2b-6d07-4b52-96df-d7b3cfebfc61",
  "category": "machine.telemetry",
  "type": "E"
}
```