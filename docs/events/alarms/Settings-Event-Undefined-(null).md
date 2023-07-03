---
layout: page
title: "Settings Event - Undefined"
---

# Settings Event - Undefined

## Type:

E

## Category:

machine.telemetry

## Description: 

Settings Event - Undefined (null)

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
    "dateTime": "2023-06-12T13:12:44.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Settings Event - Undefined",
  "id": "eddf887d-3fd3-4e27-a9bd-334f28dfdc23",
  "category": "machine.telemetry",
  "type": "E"
}
```
