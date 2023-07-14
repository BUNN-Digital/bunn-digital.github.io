---
title: "Recipe Drained"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Recipe Drained

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

recipe.drained

## Category:

machine.telemetry

## Description: 

Recipe Drained (recipe.drained)

## Payload Fields:

| Field | Type | Example | Description |
|:------|:-----|:--------|:------------|
| serialNumber | text | "SN1234" | The unique identifier for the machine that generated the event |
| datapointId | text | "68\|E\|8000.10000" | Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific. |

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "recipe.drained",
  "description": "Recipe Drained",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "recipeAgeAtTimeOfDrainMinutes": "91",
    "serialNumber": "SN1234",
    "drainDurationMilliseconds": "38248",
    "recipeNameInfo": "Test 816 Transform",
    "drainReason": "Invalid",
    "recipeTemperatureCelcius": "84",
    "volumeDrainedMilliliters": "828",
    "datapointId": "68|D|816",
    "timestamp": "2023-04-12T19:48:15",
    "reservoirId": "3"
  }
}
```
