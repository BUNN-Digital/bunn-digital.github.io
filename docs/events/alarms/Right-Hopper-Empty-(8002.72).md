---
layout: page
title: "Right Hopper Empty"
---

# Right Hopper Empty

## Type:

E

## Category:

machine.telemetry

## Description: 

Right Hopper Empty (8002.72)

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
    "dateTime": "2023-06-12T13:12:33.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Right Hopper Empty",
  "id": "0af18905-ac63-49db-ae5e-583df2af5a5d",
  "category": "machine.telemetry",
  "type": "E"
}
```
