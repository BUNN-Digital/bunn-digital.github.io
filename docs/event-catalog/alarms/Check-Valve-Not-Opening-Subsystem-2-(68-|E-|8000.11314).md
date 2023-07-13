---
title: "Check Valve Not Opening - Subsystem 2"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Check Valve Not Opening - Subsystem 2

## Type:

68|E|8000.11314

## Category:

machine.telemetry

## Description: 

Check Valve Not Opening - Subsystem 2 (68\|E\|8000.11314)

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
    "dateTime": "2023-07-10T21:07:53.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11314"
  },
  "description": "Check Valve Not Opening - Subsystem 2",
  "_id": "e3ffa1d7-1a2f-4395-8ccf-2113e962e3b6",
  "label": "Check Valve Not Opening - Subsystem 2",
  "eventType": "68\\|E\\|8000.11314",
  "category": "machine.telemetry",
  "type": "68|E|8000.11314"
}
```
