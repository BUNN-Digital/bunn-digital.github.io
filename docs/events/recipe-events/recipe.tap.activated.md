# recipe.tap.activated

## Category:

asset.telemetry

## Description: 

Describes a tap activation event on a machine.

## Payload: (JSON Schema?)

```
{
  "serialNumber": "String",
  "sentTimestampLocal": "ISO-8601 Timestamp",
  "tapId": "String",
  "reservoirId": "String",
  "tapAvailability": "String",
  "tapAvailabilityReason": "String",
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
  "type": "recipe.tap.activated",
  "description": "Recipe Position Status - Non Portion Controlled",
  "receivedTimestampUtc": "2023-01-01T00:00:00.000000000Z",
  "payload": {
    "serialNumber": "B2B0123456",
    "sentTimestampLocal": "2023-01-01T00:00:00.123456789",
    "tapId": "2",
    "reservoirId": "2",
    "tapAvailability": "Available",
    "tapAvailabilityReason": "Available",
    "recipeNameInfo": "HAZELNUT",
    "productName": "",
    "altProductName": ""
  }
}
```
