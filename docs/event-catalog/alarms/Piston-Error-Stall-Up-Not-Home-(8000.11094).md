---
title: "Piston Error Stall Up Not Home"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Piston Error Stall Up Not Home

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Up Not Home (8000.11094)

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
    "dateTime": "2023-06-12T13:10:43.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Up Not Home",
  "id": "35040301-b0a0-455a-a9ca-bb5241bcaba6",
  "category": "machine.telemetry",
  "type": "E"
}
```
