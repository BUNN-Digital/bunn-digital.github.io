layout: page
title: "Bean Hopper Mismatch Active"

# Bean Hopper Mismatch Active

## Type:

E

## Category:

machine.telemetry

## Description: 

Bean Hopper Mismatch Active (8002.251)

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
    "dateTime": "2023-06-12T13:11:46.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Bean Hopper Mismatch Active",
  "id": "3c212b25-b38c-4c5e-890a-3c94858bd676",
  "category": "machine.telemetry",
  "type": "E"
}
```
