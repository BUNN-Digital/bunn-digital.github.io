---
title: "Finish Tank Sensor Open"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Finish Tank Sensor Open

## Type:

E

## Category:

machine.telemetry

## Description: 

Finish Tank Sensor Open (8000.11062)

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
    "dateTime": "2023-06-12T13:10:21.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Finish Tank Sensor Open",
  "id": "5e2ff819-3a9a-4778-bc7c-b664219fb77b",
  "category": "machine.telemetry",
  "type": "E"
}
```
