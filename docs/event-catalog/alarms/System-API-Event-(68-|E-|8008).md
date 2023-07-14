---
title: "System API Event"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# System API Event

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

68\|E\|8008

## Category:

machine.telemetry

## Description: 

System API Event (68\|E\|8008)

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "68|E|8008",
  "description": "System API Event",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "serialNumber": "SN1234",
    "decimal": "75",
    "datapointId": "68|E|8008"
  }
}
```

## Payload Description

```
[
  null,
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

