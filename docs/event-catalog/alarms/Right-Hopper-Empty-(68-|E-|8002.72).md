---
title: "Right Hopper Empty"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Right Hopper Empty

## Type:

68\|E\|8002.72

## Category:

machine.telemetry

## Description: 

Right Hopper Empty (68\|E\|8002.72)

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
    "dateTime": "2023-07-10T21:08:50.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.72"
  },
  "description": "Right Hopper Empty",
  "_id": "f6742cd4-e77f-45e8-85fa-2c87b9def973",
  "label": "Right Hopper Empty",
  "category": "machine.telemetry",
  "type": "68\\|E\\|8002.72"
}
```
