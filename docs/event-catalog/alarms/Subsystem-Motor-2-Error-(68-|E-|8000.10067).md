---
title: "Subsystem/Motor 2 Error"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Subsystem/Motor 2 Error

## Type:

68\|E\|8000.10067

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 2 Error (68\|E\|8000.10067)

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
    "dateTime": "2023-07-10T21:06:49.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.10067"
  },
  "description": "Subsystem/Motor 2 Error",
  "_id": "06935093-538f-4a2c-9a05-2015f271a972",
  "label": "Subsystem/Motor 2 Error",
  "category": "machine.telemetry",
  "type": "68\\|E\\|8000.10067"
}
```
