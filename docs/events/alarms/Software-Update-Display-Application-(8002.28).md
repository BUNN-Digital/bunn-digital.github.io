---
layout: page
title: "Software Update - Display Application"
---

# Software Update - Display Application

## Type:

E

## Category:

machine.telemetry

## Description: 

Software Update - Display Application (8002.28)

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
    "dateTime": "2023-06-12T13:11:56.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Software Update - Display Application",
  "id": "c9aa97c0-bac2-47d3-9cb4-ae075ec92724",
  "category": "machine.telemetry",
  "type": "E"
}
```