---
layout: page
title: "Lost of Communication (Display - Control Boards)"
---

# Lost of Communication (Display - Control Boards)

## Type:

E

## Category:

machine.telemetry

## Description: 

Lost of Communication (Display - Control Boards) (null)

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
    "dateTime": "2023-06-12T13:10:12.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Lost of Communication (Display - Control Boards)",
  "id": "61dfb161-14c1-4584-91e2-f7c3dcee3734",
  "category": "machine.telemetry",
  "type": "E"
}
```
