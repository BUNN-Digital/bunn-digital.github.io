---
title: "Machine Name"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Machine Name

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

68\|A\|8124

## Category:

machine.telemetry

## Description: 

Machine Name (68\|A\|8124)

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "68|A|8124",
  "description": "Machine Name",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "serialNumber": "SN1234",
    "text": "false",
    "datapointId": "68|A|8124"
  }
}
```

## Payload Description

```
[
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "SN1234"
  },
  {
    "fieldName": "text",
    "type": "text",
    "descrtiption": "Unspecified text value.",
    "example": "This is a text value."
  },
  {
    "fieldName": "datapointId",
    "type": "text",
    "descrtiption": "Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific.",
    "example": "68|E|8000.10000"
  }
]
```

