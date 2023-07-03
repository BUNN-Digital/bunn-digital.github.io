# Reservoir 3 Not In Place

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir 3 Not In Place (8000.11331)

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
    "dateTime": "2023-06-12T13:11:31.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir 3 Not In Place",
  "id": "774ca38d-d6c3-410c-bc3d-72b5a9a537a0",
  "category": "machine.telemetry",
  "type": "E"
}
```
