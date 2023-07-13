---
title: "Right Grinder Overcurrent Shutdown"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Right Grinder Overcurrent Shutdown

## Type:

68|E|8000.11032

## Category:

machine.telemetry

## Description: 

Right Grinder Overcurrent Shutdown (68\|E\|8000.11032)

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
    "dateTime": "2023-07-10T21:06:56.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11032"
  },
  "description": "Right Grinder Overcurrent Shutdown",
  "_id": "fa24a50c-5280-4be3-ad80-6e50f210648f",
  "label": "Right Grinder Overcurrent Shutdown",
  "eventType": "68\\|E\\|8000.11032",
  "category": "machine.telemetry",
  "type": "68|E|8000.11032"
}
```
