---
title: "Cleaning Started"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Cleaning Started

## Type:

E

## Category:

machine.telemetry

## Description: 

Cleaning Started (null)

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
    "dateTime": "2023-06-12T13:12:00.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Cleaning Started",
  "id": "b4cf6d99-52db-4bde-9850-5e562e183f82",
  "category": "machine.telemetry",
  "type": "E"
}
```
