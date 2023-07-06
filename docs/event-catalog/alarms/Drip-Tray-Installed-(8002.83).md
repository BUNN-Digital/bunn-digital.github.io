---
title: "Drip Tray Installed"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Drip Tray Installed

## Type:

E

## Category:

machine.telemetry

## Description: 

Drip Tray Installed (8002.83)

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
    "dateTime": "2023-06-12T13:12:42.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Drip Tray Installed",
  "id": "8d964105-a3a5-4777-8327-511796c06d8c",
  "category": "machine.telemetry",
  "type": "E"
}
```
