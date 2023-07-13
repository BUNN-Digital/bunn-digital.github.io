---
title: "Software Update - HIgh Voltage Control Board Application"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Software Update - HIgh Voltage Control Board Application

## Type:

68|E|8002.50

## Category:

machine.telemetry

## Description: 

Software Update - HIgh Voltage Control Board Application (68\|E\|8002.50)

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
    "datapointId": "68|E|8002.50"
  },
  "description": "Software Update - HIgh Voltage Control Board Application",
  "_id": "b1e19dd4-1474-474d-a8a8-dfc29a8823bf",
  "label": "Software Update - HIgh Voltage Control Board Application",
  "eventType": "68\\|E\\|8002.50",
  "category": "machine.telemetry",
  "type": "68|E|8002.50"
}
```
