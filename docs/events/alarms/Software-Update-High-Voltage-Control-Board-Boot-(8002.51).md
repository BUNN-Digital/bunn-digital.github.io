layout: page
title: "Software Update - High Voltage Control Board Boot"

# Software Update - High Voltage Control Board Boot

## Type:

E

## Category:

machine.telemetry

## Description: 

Software Update - High Voltage Control Board Boot (8002.51)

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
    "dateTime": "2023-06-12T13:12:15.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false"
  },
  "description": "Software Update - High Voltage Control Board Boot",
  "id": "4f7f8327-d8a6-4b08-9f1f-b2e9c51cca84",
  "category": "machine.telemetry",
  "type": "E"
}
```
