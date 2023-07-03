---
#layout: minimal
title: "High Voltage IO Boot Software Needs Updated"
---

# High Voltage IO Boot Software Needs Updated

## Type:

E

## Category:

machine.telemetry

## Description: 

High Voltage IO Boot Software Needs Updated (8002.59)

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
    "dateTime": "2023-06-12T13:12:21.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "High Voltage IO Boot Software Needs Updated",
  "id": "21a0f810-4f33-40ee-aba2-3847bc066b04",
  "category": "machine.telemetry",
  "type": "E"
}
```
