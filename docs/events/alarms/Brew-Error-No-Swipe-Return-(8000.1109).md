# Brew Error No Swipe Return

## Type:

E

## Category:

machine.telemetry

## Description: 

Brew Error No Swipe Return (8000.1109)

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
    "dateTime": "2023-06-12T13:10:40.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Brew Error No Swipe Return",
  "id": "e4da6a46-d17e-4043-afcf-90cbae92133f",
  "category": "machine.telemetry",
  "type": "E"
}
```
