---
layout: minimal
title: "Serial Port 1 Loss of Communications"
parent: Alarms
---

# Serial Port 1 Loss of Communications

## Type:

E

## Category:

machine.telemetry

## Description: 

Serial Port 1 Loss of Communications (null)

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
    "dateTime": "2023-06-12T13:11:10.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Serial Port 1 Loss of Communications",
  "id": "0d1252a8-8bad-4aac-afbc-b72b77866276",
  "category": "machine.telemetry",
  "type": "E"
}
```
