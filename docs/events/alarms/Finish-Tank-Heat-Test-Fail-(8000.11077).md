---
layout: minimal
title: "Finish Tank Heat Test Fail"
parent: Alarms
---

# Finish Tank Heat Test Fail

## Type:

E

## Category:

machine.telemetry

## Description: 

Finish Tank Heat Test Fail (8000.11077)

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
    "dateTime": "2023-06-12T13:10:32.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Finish Tank Heat Test Fail",
  "id": "4b437b9f-2125-4533-bf59-8951c3a1b24d",
  "category": "machine.telemetry",
  "type": "E"
}
```
