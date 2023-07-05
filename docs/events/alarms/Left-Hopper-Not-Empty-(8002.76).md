---
layout: minimal
title: "Left Hopper Not Empty"
---

# Left Hopper Not Empty

## Type:

E

## Category:

machine.telemetry

## Description: 

Left Hopper Not Empty (8002.76)

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
  "description": "Left Hopper Not Empty",
  "id": "6e45cb4f-4b55-46ca-ad7f-e239ac9cfdb6",
  "category": "machine.telemetry",
  "type": "E"
}
```
