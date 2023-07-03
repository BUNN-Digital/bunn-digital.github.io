---
#layout: minimal
title: "Software Update - Control Board Boot"
---

# Software Update - Control Board Boot

## Type:

E

## Category:

machine.telemetry

## Description: 

Software Update - Control Board Boot (null)

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
    "dateTime": "2023-06-12T13:12:06.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Software Update - Control Board Boot",
  "id": "dc40e4b5-8ef7-4297-878f-c06f35b95dfc",
  "category": "machine.telemetry",
  "type": "E"
}
```
