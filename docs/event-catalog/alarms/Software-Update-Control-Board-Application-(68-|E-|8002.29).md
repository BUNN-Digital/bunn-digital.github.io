---
title: "Software Update - Control Board Application"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Software Update - Control Board Application

## Type:

68|E|8002.29

## Category:

machine.telemetry

## Description: 

Software Update - Control Board Application (68\|E\|8002.29)

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
    "dateTime": "2023-07-10T21:08:26.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8002.29"
  },
  "description": "Software Update - Control Board Application",
  "_id": "8301a61c-d6bd-48db-8259-2483e0856bfe",
  "label": "Software Update - Control Board Application",
  "eventType": "68\\|E\\|8002.29",
  "category": "machine.telemetry",
  "type": "68|E|8002.29"
}
```
