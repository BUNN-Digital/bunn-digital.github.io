---
#layout: minimal
title: "Cleaning Interrupted Subsystem - Hot Coffee"
---

# Cleaning Interrupted Subsystem - Hot Coffee

## Type:

E

## Category:

machine.telemetry

## Description: 

Cleaning Interrupted Subsystem - Hot Coffee (8000.11156)

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
    "dateTime": "2023-06-12T13:11:04.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Cleaning Interrupted Subsystem - Hot Coffee",
  "id": "e1f926f5-62c9-45f9-bd6b-b55f4422f74f",
  "category": "machine.telemetry",
  "type": "E"
}
```
