layout: page
title: "Left Hopper Empty"

# Left Hopper Empty

## Type:

E

## Category:

machine.telemetry

## Description: 

Left Hopper Empty (8002.73)

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
    "dateTime": "2023-06-12T13:12:33.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Left Hopper Empty",
  "id": "262c3e66-e7a2-4109-9f1c-d30f7e50fbd8",
  "category": "machine.telemetry",
  "type": "E"
}
```
