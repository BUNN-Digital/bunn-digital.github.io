---
layout: page
title: "Model Change"
---

# Model Change

## Type:

E

## Category:

machine.telemetry

## Description: 

Model Change (8002.61)

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
    "dateTime": "2023-06-12T13:12:23.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Model Change",
  "id": "918141e8-2c2b-4cdc-9a38-803370d14f25",
  "category": "machine.telemetry",
  "type": "E"
}
```
