---
title: "New Recipe Added"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# New Recipe Added

## Type:

68|E|8002.38

## Category:

machine.telemetry

## Description: 

New Recipe Added (68\|E\|8002.38)

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
    "dateTime": "2023-07-10T21:08:31.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.38"
  },
  "description": "New Recipe Added",
  "_id": "01adf2a6-6a6e-4139-83f6-8525ff8fd58b",
  "label": "New Recipe Added",
  "eventType": "68\\|E\\|8002.38",
  "category": "machine.telemetry",
  "type": "68|E|8002.38"
}
```
