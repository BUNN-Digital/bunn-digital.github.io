# Reservoir Access Door Closed

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir Access Door Closed (8002.232)

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
    "dateTime": "2023-06-12T13:11:32.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir Access Door Closed",
  "id": "b5ed7062-cd6d-4724-ab0d-aa9987e7e4f1",
  "category": "machine.telemetry",
  "type": "E"
}
```
