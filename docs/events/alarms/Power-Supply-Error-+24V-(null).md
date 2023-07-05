---
title: "Power Supply Error +24V"
layout: minimal
parent: Alarms
---

# Power Supply Error +24V

## Type:

E

## Category:

machine.telemetry

## Description: 

Power Supply Error +24V (null)

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
    "dateTime": "2023-06-12T13:10:04.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Power Supply Error +24V",
  "id": "520479ee-4109-4778-8240-9c4405500edb",
  "category": "machine.telemetry",
  "type": "E"
}
```
