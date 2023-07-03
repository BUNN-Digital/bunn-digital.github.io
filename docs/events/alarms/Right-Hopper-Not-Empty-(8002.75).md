---
#layout: minimal
title: "Right Hopper Not Empty"
---

# Right Hopper Not Empty

## Type:

E

## Category:

machine.telemetry

## Description: 

Right Hopper Not Empty (8002.75)

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
    "dateTime": "2023-06-12T13:12:35.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Right Hopper Not Empty",
  "id": "77104a6c-7c43-48a1-acf0-c23dfd5e6ba3",
  "category": "machine.telemetry",
  "type": "E"
}
```
