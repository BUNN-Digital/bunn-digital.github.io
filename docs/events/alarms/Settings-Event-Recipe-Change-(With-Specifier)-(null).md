---
title: "Settings Event - Recipe Change (With Specifier)"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Settings Event - Recipe Change (With Specifier)

## Type:

E

## Category:

machine.telemetry

## Description: 

Settings Event - Recipe Change (With Specifier) (null)

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
    "dateTime": "2023-06-12T13:12:45.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Settings Event - Recipe Change (With Specifier)",
  "id": "463b0d3a-a614-4356-9da0-5bf921b5bb12",
  "category": "machine.telemetry",
  "type": "E"
}
```
