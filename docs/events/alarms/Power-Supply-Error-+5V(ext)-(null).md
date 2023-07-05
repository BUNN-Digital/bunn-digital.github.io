---
title: "Power Supply Error +5V(ext)"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Power Supply Error +5V(ext)

## Type:

E

## Category:

machine.telemetry

## Description: 

Power Supply Error +5V(ext) (null)

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
    "dateTime": "2023-06-12T13:10:05.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Power Supply Error +5V(ext)",
  "id": "240badd8-19b9-40ff-b2b7-afc410451a94",
  "category": "machine.telemetry",
  "type": "E"
}
```
