---
title: "Brew Error Piston Move Timeout"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Brew Error Piston Move Timeout

## Type:

68|E|8000.11086

## Category:

machine.telemetry

## Description: 

Brew Error Piston Move Timeout (68\|E\|8000.11086)

## Payload:

```
[
  {
    "fieldName": "boolean",
    "type": "boolean",
    "descrtiption": "An unspecified boolean value. Most commonly this describes the state of the event itself - e.g. active (true) or inactive/resolved (false) if the event is an alarm",
    "example": "true"
  },
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
    "dateTime": "2023-07-10T21:07:21.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11086"
  },
  "description": "Brew Error Piston Move Timeout",
  "_id": "9bdca93f-df17-4e7c-b516-10e0c2aa49cb",
  "label": "Brew Error Piston Move Timeout",
  "eventType": "68\\|E\\|8000.11086",
  "category": "machine.telemetry",
  "type": "68|E|8000.11086"
}
```
