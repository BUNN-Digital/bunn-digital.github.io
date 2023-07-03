# Piston Error Stall Down O-Ring Entry

## Type:

E

## Category:

machine.telemetry

## Description: 

Piston Error Stall Down O-Ring Entry (null)

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
  "description": "Piston Error Stall Down O-Ring Entry",
  "id": "aeb6e1d6-7da0-4b40-a600-55d1165ccad2",
  "category": "machine.telemetry",
  "type": "E"
}
```
