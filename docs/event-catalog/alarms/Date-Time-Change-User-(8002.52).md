---
title: "Date/Time Change - User"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Date/Time Change - User

## Type:

E

## Category:

machine.telemetry

## Description: 

Date/Time Change - User (8002.52)

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
    "dateTime": "2023-06-12T13:12:15.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Date/Time Change - User",
  "id": "6a1f3f7c-7af1-40ec-b0ec-3d14f874ba8c",
  "category": "machine.telemetry",
  "type": "E"
}
```
