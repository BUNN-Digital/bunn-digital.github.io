# Tap Display Interface Missing - Subsystem 2

## Type:

E

## Category:

machine.telemetry

## Description: 

Tap Display Interface Missing - Subsystem 2 (8000.1132)

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
    "dateTime": "2023-06-12T13:11:20.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Tap Display Interface Missing - Subsystem 2",
  "id": "7ec328a1-7e0b-4605-9fb8-0cb6d79e9bdf",
  "category": "machine.telemetry",
  "type": "E"
}
```
