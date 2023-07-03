layout: page
title: "Water Flow Too Low Blockage"

# Water Flow Too Low Blockage

## Type:

E

## Category:

machine.telemetry

## Description: 

Water Flow Too Low Blockage (null)

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
    "dateTime": "2023-06-12T13:10:03.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Water Flow Too Low Blockage",
  "id": "b21234d9-2727-41b9-a53f-8667ebf61997",
  "category": "machine.telemetry",
  "type": "E"
}
```
