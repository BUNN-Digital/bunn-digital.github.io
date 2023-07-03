layout: page
title: "Reservoir Cleaning Intervention Required"

# Reservoir Cleaning Intervention Required

## Type:

E

## Category:

machine.telemetry

## Description: 

Reservoir Cleaning Intervention Required (8000.11326)

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
    "dateTime": "2023-06-12T13:11:25.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Reservoir Cleaning Intervention Required",
  "id": "d1dac474-bc5d-4aab-b327-b9f87618e69c",
  "category": "machine.telemetry",
  "type": "E"
}
```
