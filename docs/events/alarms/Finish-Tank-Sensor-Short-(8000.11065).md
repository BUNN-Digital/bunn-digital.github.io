---
title: "Finish Tank Sensor Short"
layout: minimal
parent: Alarms
---

# Finish Tank Sensor Short

## Type:

E

## Category:

machine.telemetry

## Description: 

Finish Tank Sensor Short (8000.11065)

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
    "dateTime": "2023-06-12T13:10:24.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Finish Tank Sensor Short",
  "id": "90025aab-fb3f-4a32-833d-ddd025549a91",
  "category": "machine.telemetry",
  "type": "E"
}
```
