layout: page
title: "Grounds Swiper Did Not Return"

# Grounds Swiper Did Not Return

## Type:

E

## Category:

machine.telemetry

## Description: 

Grounds Swiper Did Not Return (8000.11061)

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
    "dateTime": "2023-06-12T13:10:21.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Grounds Swiper Did Not Return",
  "id": "c4d4f9a8-6f03-43eb-8055-4a8e78446b32",
  "category": "machine.telemetry",
  "type": "E"
}
```
