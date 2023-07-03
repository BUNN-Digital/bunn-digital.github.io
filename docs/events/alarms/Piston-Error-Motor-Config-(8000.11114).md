layout: page
title: "Piston Error Motor Config"

# Piston Error Motor Config

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Motor Config (8000.11114)

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
    "dateTime": "2023-06-12T13:11:02.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Motor Config",
  "id": "3bc402d2-db01-4cf0-87cb-5279762538cf",
  "category": "machine.telemetry",
  "type": "E"
}
```
