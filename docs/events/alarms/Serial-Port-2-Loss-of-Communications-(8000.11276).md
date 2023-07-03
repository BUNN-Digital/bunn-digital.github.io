---
#layout: minimal
title: "Serial Port 2 Loss of Communications"
---

# Serial Port 2 Loss of Communications

## Type:

E

## Category:

machine.telemetry

## Description: 

Serial Port 2 Loss of Communications (8000.11276)

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
  "description": "Serial Port 2 Loss of Communications",
  "id": "5484b39b-1ceb-4e14-b612-aab2431484b6",
  "category": "machine.telemetry",
  "type": "E"
}
```
