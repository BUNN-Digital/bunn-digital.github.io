---
title: "Waste Bin Almost Full"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Waste Bin Almost Full

## Type:

68|E|8002.80

## Category:

machine.telemetry

## Description: 

Waste Bin Almost Full (68|E|8002.80)

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
    "dateTime": "2023-07-10T21:08:55.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.80"
  },
  "description": "Waste Bin Almost Full",
  "_id": "5412ddc7-65e4-421f-823d-ee9fbc6afb1c",
  "label": "Waste Bin Almost Full",
  "category": "machine.telemetry",
  "type": "68|E|8002.80"
}
```
