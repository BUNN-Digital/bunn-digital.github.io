---
title: "Subsystem/Motor 5 Error"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Subsystem/Motor 5 Error

## Type:

68\|E\|8000.10070

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 5 Error (68\|E\|8000.10070)

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
    "dateTime": "2023-07-10T21:06:51.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.10070"
  },
  "description": "Subsystem/Motor 5 Error",
  "_id": "2eed2ba8-da49-4571-bcdf-f6a7a70dde18",
  "label": "Subsystem/Motor 5 Error",
  "category": "machine.telemetry",
  "type": "68\\|E\\|8000.10070"
}
```
