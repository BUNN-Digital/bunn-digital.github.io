---
layout: minimal
title: "Cleaning Required Lockout"
---

# Cleaning Required Lockout

## Type:

E

## Category:

machine.telemetry

## Description: 

Cleaning Required Lockout (8002.81)

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
    "dateTime": "2023-06-12T13:12:41.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Cleaning Required Lockout",
  "id": "95c39d0b-a40b-47b5-bd80-02a35a907d55",
  "category": "machine.telemetry",
  "type": "E"
}
```
