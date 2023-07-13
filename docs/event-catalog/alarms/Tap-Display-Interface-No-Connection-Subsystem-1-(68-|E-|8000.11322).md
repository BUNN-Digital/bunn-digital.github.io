---
title: "Tap Display Interface No Connection - Subsystem 1"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Tap Display Interface No Connection - Subsystem 1

## Type:

68|E|8000.11322

## Category:

machine.telemetry

## Description: 

Tap Display Interface No Connection - Subsystem 1 (68\|E\|8000.11322)

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
    "dateTime": "2023-07-10T21:08:00.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11322"
  },
  "description": "Tap Display Interface No Connection - Subsystem 1",
  "_id": "b397cf59-13a7-4968-afb1-f50c157f07cb",
  "label": "Tap Display Interface No Connection - Subsystem 1",
  "eventType": "68\\|E\\|8000.11322",
  "category": "machine.telemetry",
  "type": "68|E|8000.11322"
}
```
