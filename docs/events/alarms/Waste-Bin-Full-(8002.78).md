layout: page
title: "Waste Bin Full"

# Waste Bin Full

## Type:

E

## Category:

machine.telemetry

## Description: 

Waste Bin Full (8002.78)

## Payload:

```
[
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  },
  {
    "fieldName": "text",
    "type": "text",
    "descrtiption": "Unspecified text value - awaiting more specific definition.",
    "example": "This is a text value."
  }
]
```

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-06-12T13:12:37.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Waste Bin Full",
  "id": "e494a6be-49bb-4b0a-9abb-56049c10650d",
  "category": "machine.telemetry",
  "type": "E"
}
```
