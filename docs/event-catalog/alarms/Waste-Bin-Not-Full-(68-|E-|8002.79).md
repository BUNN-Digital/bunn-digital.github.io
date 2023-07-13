---
title: "Waste Bin Not Full"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Waste Bin Not Full

## Type:

68|E|8002.79

## Category:

machine.telemetry

## Description: 

Waste Bin Not Full (68\|E\|8002.79)

## Payload:

```
[
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  },
  {
    "fieldName": "text",
    "type": "text",
    "descrtiption": "Unspecified text value.",
    "example": "This is a text value."
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
    "dateTime": "2023-07-10T21:08:54.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.79"
  },
  "description": "Waste Bin Not Full",
  "_id": "acdd6b3c-683f-4cb5-9418-d667f8a74934",
  "label": "Waste Bin Not Full",
  "eventType": "68\\|E\\|8002.79",
  "category": "machine.telemetry",
  "type": "68|E|8002.79"
}
```
