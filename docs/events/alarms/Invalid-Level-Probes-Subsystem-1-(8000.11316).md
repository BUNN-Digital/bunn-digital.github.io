# Invalid Level Probes - Subsystem 1

## Type:

E

## Category:

machine.telemetry

## Description: 

Invalid Level Probes - Subsystem 1 (8000.11316)

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
    "dateTime": "2023-06-12T13:11:15.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Invalid Level Probes - Subsystem 1",
  "id": "b1205fc0-9ecb-44ad-912c-e523331cb06f",
  "category": "machine.telemetry",
  "type": "E"
}
```
