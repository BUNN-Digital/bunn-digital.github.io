layout: page
title: "Center Grinder No Current Shutdown"

# Center Grinder No Current Shutdown

## Type:

E

## Category:

machine.telemetry

## Description: 

Center Grinder No Current Shutdown (8000.11044)

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
    "dateTime": "2023-06-12T13:10:19.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Center Grinder No Current Shutdown",
  "id": "d922ee19-8b6c-4e82-a663-46cbd6d7f485",
  "category": "machine.telemetry",
  "type": "E"
}
```
