---
title: "System API Event"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# System API Event

## Type:

68|E|8008

## Category:

machine.telemetry

## Description: 

System API Event (68|E|8008)

## Payload:

```
[
  null,
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
    "dateTime": "2023-07-10T21:09:06.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "decimal": "75",
    "datapointId": "68|E|8008"
  },
  "description": "System API Event",
  "_id": "281b80c3-c750-4191-9a16-b631cb0ef73c",
  "label": "System API Event",
  "category": "machine.telemetry",
  "type": "68|E|8008"
}
```
