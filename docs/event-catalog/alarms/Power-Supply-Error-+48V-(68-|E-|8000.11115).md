---
title: "Power Supply Error +48V"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Power Supply Error +48V

## Type:

68|E|8000.11115

## Category:

machine.telemetry

## Description: 

Power Supply Error +48V (68\|E\|8000.11115)

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
    "dateTime": "2023-07-10T21:07:42.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11115"
  },
  "description": "Power Supply Error +48V",
  "_id": "b10828bb-7fb2-46c2-90ae-7b97e86a7e82",
  "label": "Power Supply Error +48V",
  "eventType": "68\\|E\\|8000.11115",
  "category": "machine.telemetry",
  "type": "68|E|8000.11115"
}
```
