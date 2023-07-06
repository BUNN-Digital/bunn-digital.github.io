---
title: "Machine Name"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Machine Name

## Type:

E

## Category:

machine.telemetry

## Description: 

Machine Name (null)

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
    "dateTime": "2023-06-12T13:10:00.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Machine Name",
  "id": "d5d92c66-bc6e-428d-9def-65e89c385243",
  "category": "machine.telemetry",
  "type": "E"
}
```
