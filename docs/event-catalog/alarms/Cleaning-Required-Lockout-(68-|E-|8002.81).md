---
title: "Cleaning Required Lockout"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Cleaning Required Lockout

## Type:

68|E|8002.81

## Category:

machine.telemetry

## Description: 

Cleaning Required Lockout (68\|E\|8002.81)

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
    "dateTime": "2023-07-10T21:08:56.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.81"
  },
  "description": "Cleaning Required Lockout",
  "_id": "9eb1aac5-1e72-48e7-987f-586ed27dfdba",
  "label": "Cleaning Required Lockout",
  "eventType": "68\\|E\\|8002.81",
  "category": "machine.telemetry",
  "type": "68|E|8002.81"
}
```
