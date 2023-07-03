layout: page
title: "Software Update - Control Board Application"

# Software Update - Control Board Application

## Type:

E

## Category:

machine.telemetry

## Description: 

Software Update - Control Board Application (null)

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
    "dateTime": "2023-06-12T13:11:58.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Software Update - Control Board Application",
  "id": "928ee6bf-a0be-4bda-a6de-b2ded132e1d0",
  "category": "machine.telemetry",
  "type": "E"
}
```
