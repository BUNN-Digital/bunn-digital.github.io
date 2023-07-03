# Piston Error Stall Down No Latch

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Down No Latch (8000.11098)

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
    "dateTime": "2023-06-12T13:10:46.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Piston Error Stall Down No Latch",
  "id": "93683555-ceec-48ec-aaed-a07e6eeb6c92",
  "category": "machine.telemetry",
  "type": "E"
}
```
