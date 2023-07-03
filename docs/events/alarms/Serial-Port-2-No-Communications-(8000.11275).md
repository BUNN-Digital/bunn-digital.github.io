---
#layout: minimal
title: "Serial Port 2 No Communications"
---

# Serial Port 2 No Communications

## Type:

E

## Category:

machine.telemetry

## Description: 

Serial Port 2 No Communications (8000.11275)

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
    "dateTime": "2023-06-12T13:11:12.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Serial Port 2 No Communications",
  "id": "95a08708-7402-4444-9a35-1ecf192fbfbc",
  "category": "machine.telemetry",
  "type": "E"
}
```
