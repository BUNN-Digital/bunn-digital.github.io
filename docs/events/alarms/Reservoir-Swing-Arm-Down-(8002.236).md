# Reservoir Swing Arm Down

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir Swing Arm Down (8002.236)

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
    "dateTime": "2023-06-12T13:11:35.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir Swing Arm Down",
  "id": "9b1fa9dd-d755-4d94-a833-0d1d99765bf9",
  "category": "machine.telemetry",
  "type": "E"
}
```
