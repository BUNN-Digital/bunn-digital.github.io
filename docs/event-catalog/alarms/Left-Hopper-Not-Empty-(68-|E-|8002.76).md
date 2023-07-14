---
title: "Left Hopper Not Empty"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Left Hopper Not Empty

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

68\|E\|8002.76

## Category:

machine.telemetry

## Description: 

Left Hopper Not Empty (68\|E\|8002.76)

## Payload Fields:

| Field | Type | Example | Description |
|:------|:-----|:--------|:------------|
| serialNumber | text | "SN1234" | The unique identifier for the machine that generated the event |
| text | text | "This is a text value." | Unspecified text value. |
| datapointId | text | "68\|E\|8000.10000" | Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific. |

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "68|E|8002.76",
  "description": "Left Hopper Not Empty",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "serialNumber": "SN1234",
    "text": "false",
    "datapointId": "68|E|8002.76"
  }
}
```
