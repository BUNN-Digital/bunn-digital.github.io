---
layout: minimal
title: "Waste Bin Not Full"
parent: Alarms
---

# Waste Bin Not Full

## Type:

E

## Category:

machine.telemetry

## Description: 

Waste Bin Not Full (8002.79)

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
    "dateTime": "2023-06-12T13:12:39.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Waste Bin Not Full",
  "id": "53f17004-ec12-4984-a216-36fd81d1fcfc",
  "category": "machine.telemetry",
  "type": "E"
}
```
