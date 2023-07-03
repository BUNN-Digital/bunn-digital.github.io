---
#layout: minimal
title: "Bean Hopper Mismatch Inactive"
---

# Bean Hopper Mismatch Inactive

## Type:

E

## Category:

machine.telemetry

## Description: 

Bean Hopper Mismatch Inactive (8002.252)

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
    "dateTime": "2023-06-12T13:11:46.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Bean Hopper Mismatch Inactive",
  "id": "b68a559b-ffe2-4254-b934-d08de6017021",
  "category": "machine.telemetry",
  "type": "E"
}
```
