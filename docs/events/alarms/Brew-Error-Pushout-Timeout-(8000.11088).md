---
layout: page
title: "Brew Error Pushout Timeout"
---

# Brew Error Pushout Timeout

## Type:

E

## Category:

machine.telemetry

## Description: 

Brew Error Pushout Timeout (8000.11088)

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
    "dateTime": "2023-06-12T13:10:39.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Brew Error Pushout Timeout",
  "id": "0ce9058c-eb03-4fa6-aa1f-d644101965a0",
  "category": "machine.telemetry",
  "type": "E"
}
```
