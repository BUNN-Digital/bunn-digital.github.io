---
#layout: minimal
title: "Center Hopper Empty"
---

# Center Hopper Empty

## Type:

E

## Category:

machine.telemetry

## Description: 

Center Hopper Empty (8002.74)

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
    "dateTime": "2023-06-12T13:12:34.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Center Hopper Empty",
  "id": "37fa5abb-2e41-4cc5-b7ea-689a5e503a87",
  "category": "machine.telemetry",
  "type": "E"
}
```
