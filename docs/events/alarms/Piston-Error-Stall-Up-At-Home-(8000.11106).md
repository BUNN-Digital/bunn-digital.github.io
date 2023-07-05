---
title: "Piston Error Stall Up At Home"
layout: minimal
parent: Alarms
---

# Piston Error Stall Up At Home

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Up At Home (8000.11106)

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
    "dateTime": "2023-06-12T13:10:54.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Up At Home",
  "id": "cc14add2-ca25-4e93-bcf4-0a6bc00a71c4",
  "category": "machine.telemetry",
  "type": "E"
}
```
