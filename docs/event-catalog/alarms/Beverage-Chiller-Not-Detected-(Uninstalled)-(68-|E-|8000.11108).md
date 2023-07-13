---
title: "Beverage Chiller Not Detected (Uninstalled)"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Beverage Chiller Not Detected (Uninstalled)

## Type:

68|E|8000.11108

## Category:

machine.telemetry

## Description: 

Beverage Chiller Not Detected (Uninstalled) (68\|E\|8000.11108)

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
    "dateTime": "2023-07-10T21:07:36.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11108"
  },
  "description": "Beverage Chiller Not Detected (Uninstalled)",
  "_id": "d1401d56-3c11-4c3c-84b0-a2159bb83b40",
  "label": "Beverage Chiller Not Detected (Uninstalled)",
  "eventType": "68\\|E\\|8000.11108",
  "category": "machine.telemetry",
  "type": "68|E|8000.11108"
}
```
