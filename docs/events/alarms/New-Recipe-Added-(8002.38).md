---
layout: minimal
title: "New Recipe Added"
---

# New Recipe Added

## Type:

E

## Category:

machine.telemetry

## Description: 

New Recipe Added (8002.38)

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
    "dateTime": "2023-06-12T13:12:09.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "New Recipe Added",
  "id": "c76fa259-be6c-4bb2-bfc7-77879d30b317",
  "category": "machine.telemetry",
  "type": "E"
}
```
