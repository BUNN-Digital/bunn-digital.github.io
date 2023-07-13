---
title: "No Communication, Display-To-Display Private Network"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# No Communication, Display-To-Display Private Network

## Type:

68\|E\|8000.11166

## Category:

machine.telemetry

## Description: 

No Communication, Display-To-Display Private Network (68\|E\|8000.11166)

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
    "dateTime": "2023-07-10T21:07:44.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11166"
  },
  "description": "No Communication, Display-To-Display Private Network",
  "_id": "e16c0c25-c006-4855-aff4-0e6155b20f86",
  "label": "No Communication, Display-To-Display Private Network",
  "category": "machine.telemetry",
  "type": "68\\|E\\|8000.11166"
}
```
