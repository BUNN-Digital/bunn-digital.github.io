---
title: "Too Many Consecutive Errors During Automatic Brewing"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Too Many Consecutive Errors During Automatic Brewing

## Type:

68\|E\|8000.11183

## Category:

machine.telemetry

## Description: 

Too Many Consecutive Errors During Automatic Brewing (68\|E\|8000.11183)

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
    "dateTime": "2023-07-10T21:07:44.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11183"
  },
  "description": "Too Many Consecutive Errors During Automatic Brewing",
  "_id": "8f06d249-e0ab-490e-89de-39b53a3dad0e",
  "label": "Too Many Consecutive Errors During Automatic Brewing",
  "category": "machine.telemetry",
  "type": "68\\|E\\|8000.11183"
}
```
