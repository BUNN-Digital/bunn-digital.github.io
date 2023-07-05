---
title: "Piston Error Cmd While Unknown"
layout: minimal
parent: Alarms
grand_parent: Events
---

# Piston Error Cmd While Unknown

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Cmd While Unknown (8000.11092)

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
    "dateTime": "2023-06-12T13:10:42.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Cmd While Unknown",
  "id": "86760cf1-6228-4ac7-a895-b38b2766f42f",
  "category": "machine.telemetry",
  "type": "E"
}
```
