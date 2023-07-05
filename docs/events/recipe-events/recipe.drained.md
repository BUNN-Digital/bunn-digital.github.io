---
title: recipe.drained
layout: default
parent: Recipe Events
grand_parent: Events
---

# recipe.drained

## Category:

asset.telemetry

## Description: 

Describes a drain operation on a machine.

## Payload: (JSON Schema?)

```
{
  "serialNumber": "String",
  "sentTimestampLocal": "ISO-8601 Timestamp",
  "reservoirId": "String",
  "drainReason": "String",
  "recipeAgeAtTimeOfDrainMinutes": "Number",
  "recipeTemperatureCelsius": "Number",
  "volumeDrainedMilliliters": "Number",
  "drainDurationMilliseconds": "Number",
  "recipeNameInfo": "String",
  "productName": "String",
  "altProductName": "String"
}
```

## Example:

```
{
  "id": "00000000-0000-0000-0000-000000000000",
  "category": "machine.telemetry",
  "type": "recipe.drained",
  "description": "Recipe Drained - Non Portion Controlled",
  "receivedTimestampUtc": "2023-01-01T00:00:00.000000000Z",
  "payload": {
    "serialNumber": "B2B0123456",
    "timestampLocal": "2023-01-01T00:00:00.123456789",
    "sentTimestampLocal": "2023-01-01T00:00:00.123456789",
    "reservoirId": "2",
    "drainReason": "Old Coffee",
    "recipeAgeAtTimeOfDrainMinutes": 91.0,
    "recipeTemperatureCelsius": 78.0,
    "volumeDrainedMilliliters": 665.0,
    "drainDurationMilliseconds": 38998.0,
    "recipeNameInfo": "REGULAR",
    "productName": "",
    "altProductName": ""
  }
}
```
