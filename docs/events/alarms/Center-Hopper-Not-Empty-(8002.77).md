---
layout: minimal
title: "Center Hopper Not Empty"
---

# Center Hopper Not Empty

## Type:

E

## Category:

machine.telemetry

## Description: 

Center Hopper Not Empty (8002.77)

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
    "dateTime": "2023-06-12T13:12:36.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Center Hopper Not Empty",
  "id": "558d68d3-848d-4ee3-8ced-2d40a4fb3cf2",
  "category": "machine.telemetry",
  "type": "E"
}
```
