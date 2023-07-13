---
title: "Watchdog Reset"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Watchdog Reset

## Type:

68\|E\|8002.47

## Category:

machine.telemetry

## Description: 

Watchdog Reset (68\|E\|8002.47)

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
    "dateTime": "2023-07-10T21:08:32.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.47"
  },
  "description": "Watchdog Reset",
  "_id": "9d5e2969-d6f7-41bc-87dd-16a7a3ab635d",
  "label": "Watchdog Reset",
  "category": "machine.telemetry",
  "type": "68\\|E\\|8002.47"
}
```
