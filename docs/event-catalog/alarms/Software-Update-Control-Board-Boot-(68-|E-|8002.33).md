---
title: "Software Update - Control Board Boot"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Software Update - Control Board Boot

## Type:

68|E|8002.33

## Category:

machine.telemetry

## Description: 

Software Update - Control Board Boot (68\|E\|8002.33)

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
    "dateTime": "2023-07-10T21:08:30.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.33"
  },
  "description": "Software Update - Control Board Boot",
  "_id": "54c3f7a5-68ab-4cf3-9b4e-c835ec6d5169",
  "label": "Software Update - Control Board Boot",
  "eventType": "68\\|E\\|8002.33",
  "category": "machine.telemetry",
  "type": "68|E|8002.33"
}
```
