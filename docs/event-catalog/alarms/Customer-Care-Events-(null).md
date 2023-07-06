---
title: "Customer Care Events"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Customer Care Events

## Type:

E

## Category:

machine.telemetry

## Description: 

Customer Care Events (null)

## Payload:

```
[
  null,
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
    "dateTime": "2023-06-12T13:12:48.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "decimal": "15"
  },
  "description": "Customer Care Events",
  "id": "04da71ba-b845-4a19-893d-b8cd307c7bc0",
  "category": "machine.telemetry",
  "type": "E"
}
```
