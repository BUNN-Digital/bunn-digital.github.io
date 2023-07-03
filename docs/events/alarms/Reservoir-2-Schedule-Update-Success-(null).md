layout: page
title: "Reservoir 2 Schedule Update Success"

# Reservoir 2 Schedule Update Success

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 2 Schedule Update Success (null)

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
    "dateTime": "2023-06-12T13:11:39.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 2 Schedule Update Success",
  "id": "e23124c3-f477-4cd9-ab2b-a3a819f8dfc0",
  "category": "machine.telemetry",
  "type": "E"
}
```
