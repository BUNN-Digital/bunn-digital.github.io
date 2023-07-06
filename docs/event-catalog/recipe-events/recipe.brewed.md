---
title: recipe.brewed
layout: default
parent: "Recipe Events"
grand_parent: "Event Catalog"
---

# recipe.brewed

## Category:

asset.telemetry

## Description: 

Describes a brew operation on a machine.

## Payload: (JSON Schema?)

```
{
  "serialNumber": "String",
  "sentTimestampLocal": "ISO-8601 Timestamp",
  "recipeSize": "String",
  "reservoirId": "String",
  "recipeVolumeMilliliters": "Number",
  "recipeHoldVolumeMilliliters": "Number",
  "recipeHoldTemperatureCelsius": "Number",
  "amountOfProductUsedInRecipeGrams": "Number",
  "alternateAmountOfProductUsedInRecipeGrams": "Number",
  "timeForBrewWaitingToStartMilliseconds": "Number",
  "totalTimeOfBrewOnceStartedMilliseconds": "Number",
  "brewReason": "String",
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
  "type": "recipe.brewed",
  "description": "Recipe Brewed - Non Portion Controlled",
  "receivedTimestampUtc": "2023-01-01T00:00:00.000000000Z",
  "payload": {
    "serialNumber": "B2B0123456",
    "timestampLocal": "2023-01-01T00:00:00.123456789",
    "recipeSize": "4",
    "reservoirId": "1",
    "recipeVolumeMilliliters": 946.0,
    "recipeHoldVolumeMilliliters": 0.0,
    "recipeHoldTemperatureCelsius": 77.0,
    "amountOfProductUsedInRecipeGrams": 39.9,
    "alternateAmountOfProductUsedInRecipeGrams": 0.0,
    "timeForBrewWaitingToStartMilliseconds": 79467.0,
    "totalTimeOfBrewOnceStartedMilliseconds": 193952.0,
    "brewReason": "On Demand Associate \"Fill\" button",
    "recipeNameInfo": "MAPLE COFFEE CAKE",
    "productName": "",
    "altProductName": ""
  }
}
```
