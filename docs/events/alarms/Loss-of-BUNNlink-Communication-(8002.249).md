---
layout: minimal
title: "Loss of BUNNlink Communication"
parent: Alarms
---

# Loss of BUNNlink Communication

## Type:

E

## Category:

machine.telemetry

## Description: 

Loss of BUNNlink Communication (8002.249)

## Payload:

```
[
  {
    "fieldName": "boolean",
    "type": "boolean",
    "descrtiption": "An unspecified boolean value - awaiting more specific definition. Most commonly this describes the state of the event itself - e.g. active (true) or inactive/resolved (false) if the event is an alarm",
    "example": "true"
  },
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  }
]
```

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-06-12T13:11:45.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Loss of BUNNlink Communication",
  "id": "af4106aa-a0d2-40e5-841e-bc9a04c818a4",
  "category": "machine.telemetry",
  "type": "E"
}
```
