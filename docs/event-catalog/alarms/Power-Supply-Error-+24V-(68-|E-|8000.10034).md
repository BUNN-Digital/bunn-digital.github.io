---
title: "Power Supply Error +24V"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Power Supply Error +24V

## Type:

68|E|8000.10034

## Category:

machine.telemetry

## Description: 

Power Supply Error +24V (68\|E\|8000.10034)

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
    "dateTime": "2023-07-10T21:06:40.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.10034"
  },
  "description": "Power Supply Error +24V",
  "_id": "5d7bdd31-4419-414a-9a1f-cf6d9a927ba5",
  "label": "Power Supply Error +24V",
  "eventType": "68\\|E\\|8000.10034",
  "category": "machine.telemetry",
  "type": "68|E|8000.10034"
}
```
