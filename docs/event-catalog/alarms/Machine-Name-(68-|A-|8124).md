---
title: "Machine Name"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Machine Name

## Type:

68|A|8124

## Category:

machine.telemetry

## Description: 

Machine Name (68\|A\|8124)

## Payload:

```
[
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
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

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-07-10T21:06:35.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|A|8124"
  },
  "description": "Machine Name",
  "_id": "414ed5cf-86fd-4208-b250-8ca41f2acbed",
  "label": "Machine Name",
  "eventType": "68\\|A\\|8124",
  "category": "machine.telemetry",
  "type": "68|A|8124"
}
```
