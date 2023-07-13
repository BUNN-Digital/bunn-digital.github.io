---
title: "Right Hopper Not Empty"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Right Hopper Not Empty

## Type:

68|E|8002.75

## Category:

machine.telemetry

## Description: 

Right Hopper Not Empty (68|E|8002.75)

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
    "dateTime": "2023-07-10T21:08:52.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.75"
  },
  "description": "Right Hopper Not Empty",
  "_id": "8c0d0e1d-a154-4fce-b6a5-ddb5317d6bb6",
  "label": "Right Hopper Not Empty",
  "category": "machine.telemetry",
  "type": "68|E|8002.75"
}
```
