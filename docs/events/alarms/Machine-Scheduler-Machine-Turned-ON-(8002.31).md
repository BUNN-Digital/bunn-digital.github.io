---
layout: minimal
title: "Machine Scheduler - Machine Turned ON"
---

# Machine Scheduler - Machine Turned ON

## Type:

E

## Category:

machine.telemetry

## Description: 

Machine Scheduler - Machine Turned ON (8002.31)

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
    "dateTime": "2023-06-12T13:12:04.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Machine Scheduler - Machine Turned ON",
  "id": "1467dc92-ff22-455b-940d-f9bd699e618a",
  "category": "machine.telemetry",
  "type": "E"
}
```
