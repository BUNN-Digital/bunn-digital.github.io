---
#layout: minimal
title: "IO Boot Software Needs Updated"
---

# IO Boot Software Needs Updated

## Type:

E

## Category:

machine.telemetry

## Description: 

IO Boot Software Needs Updated (8002.57)

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
    "dateTime": "2023-06-12T13:12:19.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "IO Boot Software Needs Updated",
  "id": "53bb4534-d5fd-4d88-88df-50d53d04f04e",
  "category": "machine.telemetry",
  "type": "E"
}
```
