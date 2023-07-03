layout: page
title: "Waste Bin Installed"

# Waste Bin Installed

## Type:

E

## Category:

machine.telemetry

## Description: 

Waste Bin Installed (8002.65)

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
    "dateTime": "2023-06-12T13:12:25.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Waste Bin Installed",
  "id": "eb421a66-b1f2-43b1-ba48-f6d5a55aeb24",
  "category": "machine.telemetry",
  "type": "E"
}
```
