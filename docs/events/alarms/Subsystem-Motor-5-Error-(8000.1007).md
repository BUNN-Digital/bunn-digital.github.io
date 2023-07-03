layout: page
title: "Subsystem/Motor 5 Error"

# Subsystem/Motor 5 Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 5 Error (8000.1007)

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
    "dateTime": "2023-06-12T13:10:09.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Subsystem/Motor 5 Error",
  "id": "e3696b36-b46a-484f-8684-f2b4d18ea680",
  "category": "machine.telemetry",
  "type": "E"
}
```
