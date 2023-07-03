---
#layout: minimal
title: "Model Configuration Invalid"
---

# Model Configuration Invalid

## Type:

E

## Category:

machine.telemetry

## Description: 

Model Configuration Invalid (8000.11039)

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
    "dateTime": "2023-06-12T13:10:16.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Model Configuration Invalid",
  "id": "aafd6a25-826a-4361-80c4-8a0810f811e9",
  "category": "machine.telemetry",
  "type": "E"
}
```
