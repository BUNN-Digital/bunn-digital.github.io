---
title: "Machine Interface Activation"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Machine Interface Activation

## Type:

E

## Category:

machine.telemetry

## Description: 

Machine Interface Activation (null)

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
    "dateTime": "2023-06-12T13:12:31.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Machine Interface Activation",
  "id": "2887bfa6-7bfb-4b01-a61f-333e1005ce41",
  "category": "machine.telemetry",
  "type": "E"
}
```
