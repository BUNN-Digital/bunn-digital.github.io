---
#layout: minimal
title: "Loss of Communication (Display - PLC Board)"
---

# Loss of Communication (Display - PLC Board)

## Type:

E

## Category:

machine.telemetry

## Description: 

Loss of Communication (Display - PLC Board) (null)

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
    "dateTime": "2023-06-12T13:10:19.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Loss of Communication (Display - PLC Board)",
  "id": "9fbc22ef-014f-4df6-817f-9ab72744b124",
  "category": "machine.telemetry",
  "type": "E"
}
```
