layout: page
title: "Piston Error Stall Down Latched"

# Piston Error Stall Down Latched

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Down Latched (8000.11102)

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
    "dateTime": "2023-06-12T13:10:51.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Down Latched",
  "id": "e22779c0-6415-4ce7-b543-815ffec5e08c",
  "category": "machine.telemetry",
  "type": "E"
}
```
