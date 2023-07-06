---
title: "Machine in Standby Mode"
#layout: minimal
layout: default
parent: Alarms
grand_parent: Events
---

# Machine in Standby Mode

## Type:

E

## Category:

machine.telemetry

## Description: 

Machine in Standby Mode (8002.237)

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
    "dateTime": "2023-06-12T13:11:36.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Machine in Standby Mode",
  "id": "21fd59ac-11aa-47f3-8776-f2de8e69aa77",
  "category": "machine.telemetry",
  "type": "E"
}
```
