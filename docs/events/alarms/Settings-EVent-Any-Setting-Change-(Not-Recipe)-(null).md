---
layout: page
title: "Settings EVent - Any Setting Change (Not Recipe)"
---

# Settings EVent - Any Setting Change (Not Recipe)

## Type:

E

## Category:

machine.telemetry

## Description: 

Settings EVent - Any Setting Change (Not Recipe) (null)

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
  "description": "Settings EVent - Any Setting Change (Not Recipe)",
  "id": "75f23a0f-3ae9-4e86-9193-f5db9a5438ec",
  "category": "machine.telemetry",
  "type": "E"
}
```
