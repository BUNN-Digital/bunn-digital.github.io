---
title: "Piston Error Motor Config"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Piston Error Motor Config

## Type:

68|E|8000.11114

## Category:

machine.telemetry

## Description: 

Piston Error Motor Config (68|E|8000.11114)

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
    "dateTime": "2023-07-10T21:07:41.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11114"
  },
  "description": "Piston Error Motor Config",
  "_id": "33baf557-a924-486c-8be9-b3de1d4fe2f0",
  "label": "Piston Error Motor Config",
  "category": "machine.telemetry",
  "type": "68|E|8000.11114"
}
```
