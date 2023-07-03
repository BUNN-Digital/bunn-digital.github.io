# Brew Error Grind Timeout

## Type:

E

## Category:

machine.telemetry

## Description: 

Brew Error Grind Timeout (8000.11085)

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
    "dateTime": "2023-06-12T13:10:35.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Brew Error Grind Timeout",
  "id": "ae9776e9-b390-4066-9661-995dfe924e9e",
  "category": "machine.telemetry",
  "type": "E"
}
```
