layout: page
title: "Operator Door Open"

# Operator Door Open

## Type:

E

## Category:

machine.telemetry

## Description: 

Operator Door Open (8002.62)

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
    "dateTime": "2023-06-12T13:12:23.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Operator Door Open",
  "id": "f78cbe94-939d-4cc4-8b6a-e9c7939acb23",
  "category": "machine.telemetry",
  "type": "E"
}
```
