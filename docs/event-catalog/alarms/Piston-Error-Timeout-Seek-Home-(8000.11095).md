---
title: "Piston Error Timeout Seek Home"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Piston Error Timeout Seek Home

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Timeout Seek Home (8000.11095)

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
    "dateTime": "2023-06-12T13:10:44.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Timeout Seek Home",
  "id": "8101a5ec-fea2-43c6-8b7f-9c4a7d818411",
  "category": "machine.telemetry",
  "type": "E"
}
```
