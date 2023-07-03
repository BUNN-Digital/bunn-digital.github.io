layout: page
title: "Preheat Tank Heat Test Fail"

# Preheat Tank Heat Test Fail

## Type:

E

## Category:

machine.telemetry

## Description: 

Preheat Tank Heat Test Fail (8000.11078)

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
  "description": "Preheat Tank Heat Test Fail",
  "id": "df645257-0a04-4cf8-a8ab-c52f7d64d874",
  "category": "machine.telemetry",
  "type": "E"
}
```
