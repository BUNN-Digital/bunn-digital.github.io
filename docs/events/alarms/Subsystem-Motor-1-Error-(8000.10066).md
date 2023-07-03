# Subsystem/Motor 1 Error

## Type:

E

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 1 Error (8000.10066)

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
    "dateTime": "2023-06-12T13:10:06.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Subsystem/Motor 1 Error",
  "id": "28d7f1f6-bcc7-4b6f-8c45-57ce767c52ae",
  "category": "machine.telemetry",
  "type": "E"
}
```
