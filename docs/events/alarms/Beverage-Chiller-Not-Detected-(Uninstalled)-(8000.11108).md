# Beverage Chiller Not Detected (Uninstalled)

## Type:

E

## Category:

machine.telemetry

## Description: 

Beverage Chiller Not Detected (Uninstalled) (8000.11108)

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
    "dateTime": "2023-06-12T13:10:56.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Beverage Chiller Not Detected (Uninstalled)",
  "id": "278e6eb8-295d-49ff-9e9b-f8a497ae5e91",
  "category": "machine.telemetry",
  "type": "E"
}
```
