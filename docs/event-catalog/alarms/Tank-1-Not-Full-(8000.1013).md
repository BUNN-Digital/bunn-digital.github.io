---
title: "Tank 1 Not Full"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Tank 1 Not Full

## Type:

E

## Category:

machine.telemetry

## Description: 

Tank 1 Not Full (8000.1013)

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
    "dateTime": "2023-06-12T13:10:10.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Tank 1 Not Full",
  "id": "a770d7f7-655a-4b07-a364-c9a3293eb1a0",
  "category": "machine.telemetry",
  "type": "E"
}
```
