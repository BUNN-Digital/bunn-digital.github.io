---
layout: minimal
title: "Waste Bin Almost Full"
---

# Waste Bin Almost Full

## Type:

E

## Category:

machine.telemetry

## Description: 

Waste Bin Almost Full (8002.8)

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
    "dateTime": "2023-06-12T13:12:40.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Waste Bin Almost Full",
  "id": "4c53b9bc-c3df-4a5d-aa50-51c731ac3f44",
  "category": "machine.telemetry",
  "type": "E"
}
```
