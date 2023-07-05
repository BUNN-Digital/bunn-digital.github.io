---
layout: minimal
title: "Cleaning Due Soon"
parent: Alarms
---

# Cleaning Due Soon

## Type:

E

## Category:

machine.telemetry

## Description: 

Cleaning Due Soon (8002.6)

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
    "dateTime": "2023-06-12T13:12:21.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Cleaning Due Soon",
  "id": "c9f4e71e-9439-498b-a4ab-fba871baa582",
  "category": "machine.telemetry",
  "type": "E"
}
```
