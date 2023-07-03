layout: page
title: "Inlet Tank Sensor Open"

# Inlet Tank Sensor Open

## Type:

E

## Category:

machine.telemetry

## Description: 

Inlet Tank Sensor Open (8000.11064)

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
    "dateTime": "2023-06-12T13:10:23.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Inlet Tank Sensor Open",
  "id": "1f6dff3c-847b-4ebb-b47e-a058601313be",
  "category": "machine.telemetry",
  "type": "E"
}
```
