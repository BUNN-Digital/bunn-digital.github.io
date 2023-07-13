---
title: "Settings EVent - Any Setting Change (Not Recipe)"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Settings EVent - Any Setting Change (Not Recipe)

## Type:

68|E|8003.1

## Category:

machine.telemetry

## Description: 

Settings EVent - Any Setting Change (Not Recipe) (68|E|8003.1)

## Payload:

```
[
  {
    "fieldName": "boolean",
    "type": "boolean",
    "descrtiption": "An unspecified boolean value. Most commonly this describes the state of the event itself - e.g. active (true) or inactive/resolved (false) if the event is an alarm",
    "example": "true"
  },
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  },
  {
    "fieldName": "datapointId",
    "type": "text",
    "descrtiption": "Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific.",
    "example": "68|E|8000.10000"
  }
]
```

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-07-10T21:09:03.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8003.1"
  },
  "description": "Settings EVent - Any Setting Change (Not Recipe)",
  "_id": "ae3ac672-67be-433b-a21d-b15a332334d4",
  "label": "Settings EVent - Any Setting Change (Not Recipe)",
  "category": "machine.telemetry",
  "type": "68|E|8003.1"
}
```
