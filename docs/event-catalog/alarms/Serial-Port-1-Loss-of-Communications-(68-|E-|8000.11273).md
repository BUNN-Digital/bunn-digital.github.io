---
title: "Serial Port 1 Loss of Communications"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Serial Port 1 Loss of Communications

## Type:

68|E|8000.11273

## Category:

machine.telemetry

## Description: 

Serial Port 1 Loss of Communications (68\|E\|8000.11273)

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
    "dateTime": "2023-07-10T21:07:50.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11273"
  },
  "description": "Serial Port 1 Loss of Communications",
  "_id": "0f92b0e8-c199-4658-98dc-e098fd6a5150",
  "label": "Serial Port 1 Loss of Communications",
  "eventType": "68\\|E\\|8000.11273",
  "category": "machine.telemetry",
  "type": "68|E|8000.11273"
}
```
