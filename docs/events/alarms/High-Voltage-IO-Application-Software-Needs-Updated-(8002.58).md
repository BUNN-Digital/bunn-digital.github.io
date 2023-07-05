---
title: "High Voltage IO Application Software Needs Updated"
layout: minimal
parent: Alarms
grand_parent: Events
---

# High Voltage IO Application Software Needs Updated

## Type:

E

## Category:

machine.telemetry

## Description: 

High Voltage IO Application Software Needs Updated (8002.58)

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
    "dateTime": "2023-06-12T13:12:20.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "High Voltage IO Application Software Needs Updated",
  "id": "f7ce20b1-fe66-4049-88ae-64160bf0ee9f",
  "category": "machine.telemetry",
  "type": "E"
}
```
