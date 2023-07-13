---
title: "Reservoir 3 Schedule Update Failure - Name Mismatch"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Reservoir 3 Schedule Update Failure - Name Mismatch

## Type:

68|E|8002.244

## Category:

machine.telemetry

## Description: 

Reservoir 3 Schedule Update Failure - Name Mismatch (68|E|8002.244)

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
    "dateTime": "2023-07-10T21:08:15.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8002.244"
  },
  "description": "Reservoir 3 Schedule Update Failure - Name Mismatch",
  "_id": "2abb5692-7428-4047-b977-0eade6d7ccef",
  "label": "Reservoir 3 Schedule Update Failure - Name Mismatch",
  "category": "machine.telemetry",
  "type": "68|E|8002.244"
}
```
