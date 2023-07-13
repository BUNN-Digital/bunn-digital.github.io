---
title: "Cleaning Interrupted (Lockout)"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Cleaning Interrupted (Lockout)

## Type:

68|E|8002.60

## Category:

machine.telemetry

## Description: 

Cleaning Interrupted (Lockout) (68\|E\|8002.60)

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
    "dateTime": "2023-07-10T21:08:40.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.60"
  },
  "description": "Cleaning Interrupted (Lockout)",
  "_id": "b49e47d3-ed6c-4497-97b4-df0777dc2bf6",
  "label": "Cleaning Interrupted (Lockout)",
  "eventType": "68\\|E\\|8002.60",
  "category": "machine.telemetry",
  "type": "68|E|8002.60"
}
```
