# Inlet Tank Sensor Short

## Type:

E

## Category:

machine.telemetry

## Description: 

Inlet Tank Sensor Short (8000.11067)

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
    "dateTime": "2023-06-12T13:10:25.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Inlet Tank Sensor Short",
  "id": "e86a9e84-845d-4bc0-ac99-1ebef3b41a41",
  "category": "machine.telemetry",
  "type": "E"
}
```
