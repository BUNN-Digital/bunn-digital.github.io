---
title: "Reservoir 1 Schedule Update Failure - Name Mismatch"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Reservoir 1 Schedule Update Failure - Name Mismatch

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

68\|E\|8002.242

## Category:

machine.telemetry

## Description: 

Reservoir 1 Schedule Update Failure - Name Mismatch (68\|E\|8002.242)

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "68|E|8002.242",
  "description": "Reservoir 1 Schedule Update Failure - Name Mismatch",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "boolean": "false",
    "serialNumber": "SN1234",
    "datapointId": "68|E|8002.242"
  }
}
```

## Payload Description

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
    "example": "SN1234"
  },
  {
    "fieldName": "datapointId",
    "type": "text",
    "descrtiption": "Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific.",
    "example": "68|E|8000.10000"
  }
]
```

