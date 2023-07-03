---
layout: page
title: "Brew Error Pump Flow Limit"
---

# Brew Error Pump Flow Limit

## Type:

E

## Category:

machine.telemetry

## Description: 

Brew Error Pump Flow Limit (8000.11113)

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
    "dateTime": "2023-06-12T13:11:01.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Brew Error Pump Flow Limit",
  "id": "1347ae6b-cd53-408e-8311-3f8a0b2fd8c0",
  "category": "machine.telemetry",
  "type": "E"
}
```
