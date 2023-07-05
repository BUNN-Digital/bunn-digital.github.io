---
title: "Water Filter Service Due"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Water Filter Service Due

## Type:

E

## Category:

machine.telemetry

## Description: 

Water Filter Service Due (8000.11185)

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
    "dateTime": "2023-06-12T13:11:07.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Water Filter Service Due",
  "id": "a4514b69-07f1-452c-a2ee-e568c34a2ae4",
  "category": "machine.telemetry",
  "type": "E"
}
```
