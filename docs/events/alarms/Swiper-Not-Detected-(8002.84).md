---
title: "Swiper Not Detected"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Swiper Not Detected

## Type:

E

## Category:

machine.telemetry

## Description: 

Swiper Not Detected (8002.84)

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
    "dateTime": "2023-06-12T13:12:43.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Swiper Not Detected",
  "id": "7ca2d3b5-390c-49f5-b12d-a7cdd1230125",
  "category": "machine.telemetry",
  "type": "E"
}
```
