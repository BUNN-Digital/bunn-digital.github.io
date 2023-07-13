---
title: "Piston Error Stall Down No Latch"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Piston Error Stall Down No Latch

## Type:

68|E|8000.11098

## Category:

machine.telemetry

## Description: 

Piston Error Stall Down No Latch (68\|E\|8000.11098)

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
    "dateTime": "2023-07-10T21:07:31.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11098"
  },
  "description": "Piston Error Stall Down No Latch",
  "_id": "ea253f9c-cdcb-4c4c-b187-e015902bf0d7",
  "label": "Piston Error Stall Down No Latch",
  "eventType": "68\\|E\\|8000.11098",
  "category": "machine.telemetry",
  "type": "68|E|8000.11098"
}
```
