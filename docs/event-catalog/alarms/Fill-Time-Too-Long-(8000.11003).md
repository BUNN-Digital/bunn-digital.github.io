---
title: "Fill Time Too Long"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Fill Time Too Long

## Type:

E

## Category:

machine.telemetry

## Description: 

Fill Time Too Long (8000.11003)

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
    "dateTime": "2023-06-12T13:10:13.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Fill Time Too Long",
  "id": "7ba25544-fcfc-45f9-9f4d-119a162bde2e",
  "category": "machine.telemetry",
  "type": "E"
}
```
