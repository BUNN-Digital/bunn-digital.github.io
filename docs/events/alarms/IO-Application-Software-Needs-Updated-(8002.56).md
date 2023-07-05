---
title: "IO Application Software Needs Updated"
layout: minimal
parent: Alarms
grand_parent: Events
---

# IO Application Software Needs Updated

## Type:

E

## Category:

machine.telemetry

## Description: 

IO Application Software Needs Updated (8002.56)

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
    "dateTime": "2023-06-12T13:12:18.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "IO Application Software Needs Updated",
  "id": "8afac49a-52b4-4f61-bfa8-b39ee00122be",
  "category": "machine.telemetry",
  "type": "E"
}
```
