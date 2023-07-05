---
layout: minimal
title: "Grounds Swiper Did Not Extend"
---

# Grounds Swiper Did Not Extend

## Type:

E

## Category:

machine.telemetry

## Description: 

Grounds Swiper Did Not Extend (null)

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
    "dateTime": "2023-06-12T13:10:20.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Grounds Swiper Did Not Extend",
  "id": "417edcec-cae6-44f6-9662-4b0aedd28992",
  "category": "machine.telemetry",
  "type": "E"
}
```
