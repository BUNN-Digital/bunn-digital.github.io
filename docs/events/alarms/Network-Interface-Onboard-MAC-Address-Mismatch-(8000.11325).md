---
layout: minimal
title: "Network Interface Onboard MAC Address Mismatch"
parent: Alarms
---

# Network Interface Onboard MAC Address Mismatch

## Type:

E

## Category:

machine.telemetry

## Description: 

Network Interface Onboard MAC Address Mismatch (8000.11325)

## Payload:

```
[
  {
    "fieldName": "boolean",
    "type": "boolean",
    "descrtiption": "An unspecified boolean value - awaiting more specific definition. Most commonly this describes the state of the event itself - e.g. active (true) or inactive/resolved (false) if the event is an alarm",
    "example": "true"
  },
  {
    "fieldName": "serialNumber",
    "type": "text",
    "descrtiption": "The unique identifier for the machine that generated the event",
    "example": "TEST000001"
  }
]
```

## Example:

```
{
  "receivedTimestampUtc": {
    "dateTime": "2023-06-12T13:11:25.000Z",
    "zone": "UTC"
  },
  "payload": {
    "boolean": "false",
    "serialNumber": "TEST000001"
  },
  "description": "Network Interface Onboard MAC Address Mismatch",
  "id": "0b1aeb04-81f0-4509-bbde-cb775d28790c",
  "category": "machine.telemetry",
  "type": "E"
}
```
