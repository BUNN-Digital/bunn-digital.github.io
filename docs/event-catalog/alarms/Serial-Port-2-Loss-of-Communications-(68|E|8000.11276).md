---
title: "Serial Port 2 Loss of Communications"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Serial Port 2 Loss of Communications

## Type:

68|E|8000.11276

## Category:

machine.telemetry

## Description: 

Serial Port 2 Loss of Communications (68|E|8000.11276)

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
    "dateTime": "2023-07-10T21:07:52.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11276"
  },
  "description": "Serial Port 2 Loss of Communications",
  "_id": "19c80569-b6da-4f70-8fd3-320eb7acecc1",
  "label": "Serial Port 2 Loss of Communications",
  "category": "machine.telemetry",
  "type": "68|E|8000.11276"
}
```
