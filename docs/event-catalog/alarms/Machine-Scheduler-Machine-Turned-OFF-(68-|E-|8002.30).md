---
title: "Machine Scheduler - Machine Turned OFF"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Machine Scheduler - Machine Turned OFF

## Type:

68|E|8002.30

## Category:

machine.telemetry

## Description: 

Machine Scheduler - Machine Turned OFF (68\|E\|8002.30)

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
    "dateTime": "2023-07-10T21:08:29.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.30"
  },
  "description": "Machine Scheduler - Machine Turned OFF",
  "_id": "bbaed0dd-0f22-444b-9829-45e4f3b70d6c",
  "label": "Machine Scheduler - Machine Turned OFF",
  "eventType": "68\\|E\\|8002.30",
  "category": "machine.telemetry",
  "type": "68|E|8002.30"
}
```
