---
#layout: minimal
title: "Waste Bin Removed"
---

# Waste Bin Removed

## Type:

E

## Category:

machine.telemetry

## Description: 

Waste Bin Removed (8002.64)

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
    "dateTime": "2023-06-12T13:12:25.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Waste Bin Removed",
  "id": "34ddce8f-007d-4b83-b8d0-35975364486f",
  "category": "machine.telemetry",
  "type": "E"
}
```
