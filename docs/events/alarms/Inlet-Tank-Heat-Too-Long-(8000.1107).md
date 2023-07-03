# Inlet Tank Heat Too Long

## Type:

E

## Category:

machine.telemetry

## Description: 

Inlet Tank Heat Too Long (8000.1107)

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
    "dateTime": "2023-06-12T13:10:29.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Inlet Tank Heat Too Long",
  "id": "a74f67ea-0832-4d9f-9660-e4dbc33ae791",
  "category": "machine.telemetry",
  "type": "E"
}
```
