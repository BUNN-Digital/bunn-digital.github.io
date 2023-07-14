---
title: "Recipe Position Status - Non Portion Controlled"
layout: default
parent: "Alarms"
grand_parent: "Event Catalog"
---

# Recipe Position Status - Non Portion Controlled

See [Standard Format](/event-subscriptions/event-format) for a description of the standard fields.

## Type:

recipe.tap.activated

## Category:

machine.telemetry

## Description: 

Recipe Position Status - Non Portion Controlled (recipe.tap.activated)

## Payload Fields:

| Field | Type | Example | Description |
|:------|:-----|:--------|:------------|
| serialNumber | text | "SN1234" | The unique identifier for the machine that generated the event |
| datapointId | text | "68\|E\|8000.10000" | Identifies the datapoint related to this event. A datapoint is a low-level representation of machine data and/or events passed through BUNNlink. The Datapoint ID allows correlation of events from machine to BUNNlink to the Event API. The Datapoint ID is similar to event type, but is machine-specific. |

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "type": "recipe.tap.activated",
  "description": "Recipe Position Status - Non Portion Controlled",
  "receivedTimestampUtc": "1970-01-01T00:00:00.000000000Z",
  "category": "machine.telemetry",
  "payload": {
    "serialNumber": "SN1234",
    "recipeNameInfo": "Test 817 Transform",
    "datapointId": "68|D|817",
    "tapAvailability": "Not Available",
    "tapId": "2",
    "timestamp": "2023-04-12T18:26:16",
    "reservoirId": "2",
    "tapAvailabilityReason": "Unknown"
  }
}
```
