---
title: "Customer Care Events"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Customer Care Events

## Type:

68|E|8005

## Category:

machine.telemetry

## Description: 

Customer Care Events (68\|E\|8005)

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
    "dateTime": "2023-07-10T21:09:05.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "decimal": "15",
    "datapointId": "68|E|8005"
  },
  "description": "Customer Care Events",
  "_id": "0ffd2879-edf6-490a-acf7-b0f2a6768d90",
  "label": "Customer Care Events",
  "eventType": "68\\|E\\|8005",
  "category": "machine.telemetry",
  "type": "68|E|8005"
}
```
