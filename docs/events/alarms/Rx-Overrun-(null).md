---
layout: minimal
title: "Rx Overrun"
parent: Alarms
---

# Rx Overrun

## Type:

E

## Category:

machine.telemetry

## Description: 

Rx Overrun (null)

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
    "dateTime": "2023-06-12T13:12:08.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Rx Overrun",
  "id": "2215df86-02cc-4efd-bead-5deefe7114f1",
  "category": "machine.telemetry",
  "type": "E"
}
```
