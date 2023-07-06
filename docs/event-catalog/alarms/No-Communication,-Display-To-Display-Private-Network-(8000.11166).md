---
title: "No Communication, Display-To-Display Private Network"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# No Communication, Display-To-Display Private Network

## Type:

E

## Category:

machine.telemetry

## Description: 

No Communication, Display-To-Display Private Network (8000.11166)

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
    "dateTime": "2023-06-12T13:11:05.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "No Communication, Display-To-Display Private Network",
  "id": "591e508a-1618-4c40-9d8b-dc3ec6e02e4a",
  "category": "machine.telemetry",
  "type": "E"
}
```
