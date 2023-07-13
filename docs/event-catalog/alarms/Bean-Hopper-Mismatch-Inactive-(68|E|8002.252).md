---
title: "Bean Hopper Mismatch Inactive"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Bean Hopper Mismatch Inactive

## Type:

68|E|8002.252

## Category:

machine.telemetry

## Description: 

Bean Hopper Mismatch Inactive (68|E|8002.252)

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
    "dateTime": "2023-07-10T21:08:22.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8002.252"
  },
  "description": "Bean Hopper Mismatch Inactive",
  "_id": "f187bcef-7395-4d6e-9cab-b378fb8772e4",
  "label": "Bean Hopper Mismatch Inactive",
  "category": "machine.telemetry",
  "type": "68|E|8002.252"
}
```
