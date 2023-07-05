---
title: "Date/Time Change - Auto"
layout: minimal
parent: Alarms
---

# Date/Time Change - Auto

## Type:

E

## Category:

machine.telemetry

## Description: 

Date/Time Change - Auto (8002.53)

## Payload:

```
[
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  },
  {
    "fieldName": "text",
    "type": "text",
    "descrtiption": "Unspecified text value - awaiting more specific definition.",
    "example": "This is a text value."
  }
]
```

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-06-12T13:12:16.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Date/Time Change - Auto",
  "id": "91768ad4-c942-4222-b314-5ef171f32283",
  "category": "machine.telemetry",
  "type": "E"
}
```
