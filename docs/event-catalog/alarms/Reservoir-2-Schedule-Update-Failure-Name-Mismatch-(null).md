---
title: "Reservoir 2 Schedule Update Failure - Name Mismatch"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Reservoir 2 Schedule Update Failure - Name Mismatch

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 2 Schedule Update Failure - Name Mismatch (null)

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
    "dateTime": "2023-06-12T13:11:41.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 2 Schedule Update Failure - Name Mismatch",
  "id": "4fcd5ae9-383d-49cf-8b97-a0841822bf9f",
  "category": "machine.telemetry",
  "type": "E"
}
```
