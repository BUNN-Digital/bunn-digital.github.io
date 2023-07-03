---
#layout: minimal
title: "Failed To Start Beverage - Multiple Occurrences"
---

# Failed To Start Beverage - Multiple Occurrences

## Type:

E

## Category:

machine.telemetry

## Description: 

Failed To Start Beverage - Multiple Occurrences (8000.11037)

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
    "dateTime": "2023-06-12T13:10:16.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Failed To Start Beverage - Multiple Occurrences",
  "id": "d89ee2ae-5603-4d82-9145-63746fa76fb3",
  "category": "machine.telemetry",
  "type": "E"
}
```
