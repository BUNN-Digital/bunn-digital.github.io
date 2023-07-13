---
title: "Network Interface Onboard MAC Address Mismatch"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Network Interface Onboard MAC Address Mismatch

## Type:

68|E|8000.11325

## Category:

machine.telemetry

## Description: 

Network Interface Onboard MAC Address Mismatch (68|E|8000.11325)

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
    "dateTime": "2023-07-10T21:08:02.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001",
    "datapointId": "68|E|8000.11325"
  },
  "description": "Network Interface Onboard MAC Address Mismatch",
  "_id": "3faf8b26-fb93-4324-b4d6-d5bab5b7ac35",
  "label": "Network Interface Onboard MAC Address Mismatch",
  "category": "machine.telemetry",
  "type": "68|E|8000.11325"
}
```
