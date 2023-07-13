---
title: "Subsystem/Motor 4 Error"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Subsystem/Motor 4 Error

## Type:

68|E|8000.10069

## Category:

machine.telemetry

## Description: 

Subsystem/Motor 4 Error (68\|E\|8000.10069)

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
    "datapointId": "68|E|8000.10069"
  },
  "description": "Subsystem/Motor 4 Error",
  "_id": "4bc6c989-ce70-47c8-a534-7e73b3620772",
  "label": "Subsystem/Motor 4 Error",
  "eventType": "68\\|E\\|8000.10069",
  "category": "machine.telemetry",
  "type": "68|E|8000.10069"
}
```
