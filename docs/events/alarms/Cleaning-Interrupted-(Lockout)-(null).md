---
#layout: minimal
title: "Cleaning Interrupted (Lockout)"
---

# Cleaning Interrupted (Lockout)

## Type:

E

## Category:

machine.telemetry

## Description: 

Cleaning Interrupted (Lockout) (null)

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
    "dateTime": "2023-06-12T13:12:22.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Cleaning Interrupted (Lockout)",
  "id": "ab0ec43e-8324-480e-b7ab-2947af62ee25",
  "category": "machine.telemetry",
  "type": "E"
}
```
