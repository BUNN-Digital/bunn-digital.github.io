---
title: "Software Update - High Voltage Control Board Boot"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Software Update - High Voltage Control Board Boot

## Type:

68|E|8002.51

## Category:

machine.telemetry

## Description: 

Software Update - High Voltage Control Board Boot (68|E|8002.51)

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
    "dateTime": "2023-07-10T21:08:33.000Z",
    "zone": "UTC"
  },
  "payload": {
    "serialNumber": "TEST000001",
    "text": "false",
    "datapointId": "68|E|8002.51"
  },
  "description": "Software Update - High Voltage Control Board Boot",
  "_id": "0b88ee85-1bb3-49f3-b789-d0f4d6be0626",
  "label": "Software Update - High Voltage Control Board Boot",
  "category": "machine.telemetry",
  "type": "68|E|8002.51"
}
```
