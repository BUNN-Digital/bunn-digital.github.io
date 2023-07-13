---
title: "Piston Error Comm Fail"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Piston Error Comm Fail

## Type:

68|E|8000.11112

## Category:

machine.telemetry

## Description: 

Piston Error Comm Fail (68\|E\|8000.11112)

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
    "dateTime": "2023-07-10T21:07:40.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11112"
  },
  "description": "Piston Error Comm Fail",
  "_id": "42fb23b7-9f4c-4bb3-9ac7-e1029ccb1b7d",
  "label": "Piston Error Comm Fail",
  "eventType": "68\\|E\\|8000.11112",
  "category": "machine.telemetry",
  "type": "68|E|8000.11112"
}
```
