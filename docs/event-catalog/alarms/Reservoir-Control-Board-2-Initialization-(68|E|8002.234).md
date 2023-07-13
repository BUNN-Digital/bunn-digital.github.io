---
title: "Reservoir Control Board 2 Initialization"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Reservoir Control Board 2 Initialization

## Type:

68|E|8002.234

## Category:

machine.telemetry

## Description: 

Reservoir Control Board 2 Initialization (68|E|8002.234)

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
    "dateTime": "2023-07-10T21:08:10.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8002.234"
  },
  "description": "Reservoir Control Board 2 Initialization",
  "_id": "ab49c9c2-ff3e-4c8e-9e5e-43a6b637d5e3",
  "label": "Reservoir Control Board 2 Initialization",
  "category": "machine.telemetry",
  "type": "68|E|8002.234"
}
```
