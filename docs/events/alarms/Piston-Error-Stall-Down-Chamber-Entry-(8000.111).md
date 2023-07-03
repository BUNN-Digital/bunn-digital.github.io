# Piston Error Stall Down Chamber Entry

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Down Chamber Entry (8000.111)

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
    "dateTime": "2023-06-12T13:10:50.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Down Chamber Entry",
  "id": "14c57124-f092-4ea9-8487-0fc48f9624dd",
  "category": "machine.telemetry",
  "type": "E"
}
```
