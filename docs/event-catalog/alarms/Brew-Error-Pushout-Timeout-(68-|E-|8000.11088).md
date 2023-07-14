---
title: "Brew Error Pushout Timeout"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Brew Error Pushout Timeout

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

68\|E\|8000.11088

## Category:

machine.telemetry

## Description: 

Brew Error Pushout Timeout (68\|E\|8000.11088)

## Payload Fields:

| Field | Type | Example | Description |
|:------|:-----|:--------|:------------|
| serialNumber | text | "SN1234" | The unique identifier for the machine that generated the event |
| datapointId | text | "68\|E\|8000.10000" | Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific. |
| boolean | boolean | true | An unspecified boolean value. Most commonly this describes the state of the event itself - e.g. active (true) or inactive/resolved (false) if the event is an alarm |

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "68|E|8000.11088",
  "description": "Brew Error Pushout Timeout",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "boolean": "false",
    "serialNumber": "SN1234",
    "datapointId": "68|E|8000.11088"
  }
}
```
