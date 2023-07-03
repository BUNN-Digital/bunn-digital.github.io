# Water Pump Stalled

## Type:

E

## Category:

machine.telemetry

## Description: 

Water Pump Stalled (8000.10011)

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
    "dateTime": "2023-06-12T13:10:02.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Water Pump Stalled",
  "id": "ec75b6a9-9c78-484c-96b6-eec6d1970e6f",
  "category": "machine.telemetry",
  "type": "E"
}
```
