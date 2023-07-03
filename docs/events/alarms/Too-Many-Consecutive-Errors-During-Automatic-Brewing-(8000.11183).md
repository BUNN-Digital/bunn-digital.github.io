---
layout: page
title: "Too Many Consecutive Errors During Automatic Brewing"
---

# Too Many Consecutive Errors During Automatic Brewing

## Type:

E

## Category:

machine.telemetry

## Description: 

Too Many Consecutive Errors During Automatic Brewing (8000.11183)

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
    "dateTime": "2023-06-12T13:11:06.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Too Many Consecutive Errors During Automatic Brewing",
  "id": "ee8cead8-6eb0-40b9-a697-ab963898322c",
  "category": "machine.telemetry",
  "type": "E"
}
```
