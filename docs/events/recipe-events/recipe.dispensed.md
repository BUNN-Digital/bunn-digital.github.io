---
title: recipe.dispensed
layout: minimal
parent: Recipe Events
grand_parent: Events
---

# recipe.dispensed

## Category:

asset.telemetry

## Description: 

Describes a dispense operation on a machine.

## Payload: (JSON Schema?)

```
{
  "serialNumber": "String",
  "sentTimestampLocal": "ISO-8601 Timestamp",
  "tapId": "String",
  "reservoirId": "String",
  "tapAvailability": "String",
  "recipeAgeAtTimeOfDispenseMinutes": "Number",
  "recipeTemperatureCelsius": "Number",
  "volumeDispensedMilliliters": "Number",
  "tapActiveDurationMilliseconds": "Number",
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
  "type": "recipe.dispensed",
  "description": "Recipe Dispensed - Non Portion Controlled",
  "receivedTimestampUtc": "2023-01-01T00:00:00.000000000Z",
  "payload": {
    "serialNumber": "B2B0123456",
    "timestampLocal": "2023-01-01T00:00:00.123456789",
    "tapId": "1",
    "reservoirId": "1",
    "tapAvailability": "Available",
    "recipeAgeAtTimeOfDispenseMinutes": 8.0,
    "recipeTemperatureCelsius": 79.0,
    "volumeDispensedMilliliters": 408.0,
    "tapActiveDurationMilliseconds": 8178.0,
    "recipeNameInfo": "REGULAR",
    "productName": "",
    "altProductName": ""
  }
}
```
