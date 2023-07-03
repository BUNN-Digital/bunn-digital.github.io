layout: page
title: "Machine Scheduler - Machine Turned OFF"

# Machine Scheduler - Machine Turned OFF

## Type:

E

## Category:

machine.telemetry

## Description: 

Machine Scheduler - Machine Turned OFF (8002.3)

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
    "dateTime": "2023-06-12T13:12:02.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Machine Scheduler - Machine Turned OFF",
  "id": "90736830-0290-45f8-b17c-53f3a9519235",
  "category": "machine.telemetry",
  "type": "E"
}
```
