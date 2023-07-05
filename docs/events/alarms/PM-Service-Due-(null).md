---
layout: minimal
title: "PM Service Due"
---

# PM Service Due

## Type:

E

## Category:

machine.telemetry

## Description: 

PM Service Due (null)

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
    "dateTime": "2023-06-12T13:10:01.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "PM Service Due",
  "id": "4eb4cc83-3d10-4636-8f50-b155ac280a9c",
  "category": "machine.telemetry",
  "type": "E"
}
```
