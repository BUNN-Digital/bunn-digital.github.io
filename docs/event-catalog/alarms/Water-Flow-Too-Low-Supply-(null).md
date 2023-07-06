---
title: "Water Flow Too Low Supply"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Water Flow Too Low Supply

## Type:

E

## Category:

machine.telemetry

## Description: 

Water Flow Too Low Supply (null)

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
    "dateTime": "2023-06-12T13:10:34.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Water Flow Too Low Supply",
  "id": "1877a822-c6ec-4a16-8e10-d4c7ee299d4a",
  "category": "machine.telemetry",
  "type": "E"
}
```
