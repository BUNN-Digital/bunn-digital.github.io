---
title: "Brew Error Pushout Timeout"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Brew Error Pushout Timeout

## Type:

68\|E\|8000.11088

## Category:

machine.telemetry

## Description: 

Brew Error Pushout Timeout (68\|E\|8000.11088)

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
    "dateTime": "2023-07-10T21:07:22.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11088"
  },
  "description": "Brew Error Pushout Timeout",
  "_id": "ad4938a3-f224-43c6-87b1-0488494b6708",
  "label": "Brew Error Pushout Timeout",
  "category": "machine.telemetry",
  "type": "68\\|E\\|8000.11088"
}
```
