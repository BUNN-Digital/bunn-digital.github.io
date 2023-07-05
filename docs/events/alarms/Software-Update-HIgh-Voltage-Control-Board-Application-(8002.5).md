---
title: "Software Update - HIgh Voltage Control Board Application"
layout: minimal
parent: Alarms
---

# Software Update - HIgh Voltage Control Board Application

## Type:

E

## Category:

machine.telemetry

## Description: 

Software Update - HIgh Voltage Control Board Application (8002.5)

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
    "dateTime": "2023-06-12T13:12:14.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Software Update - HIgh Voltage Control Board Application",
  "id": "c875a496-888b-4afd-937d-22874c002889",
  "category": "machine.telemetry",
  "type": "E"
}
```
