layout: page
title: "Recipe Brewed"

# Recipe Brewed

## Type:

BrewEvent

## Category:

machine.telemetry

## Description: 

Recipe Brewed (null)

## Payload:

```
[
  null,
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
    "dateTime": "2023-06-12T15:41:17.000Z",
    "zone": "UTC"
  },
  "payload": {
    "recipeVolumeMilliliters": "739",
    "recipeSize": "5",
    "serialNumber": "TEST000001",
    "timeForBrewWaitingToStartMilliseconds": "181974",
    "recipeNameInfo": "JR Automated Test 814",
    "totalTimeOfBrewOnceStartedMilliseconds": "260452",
    "amountOfProductUsedInRecipeGrams": "31.7",
    "recipeHoldTemperatureCelcius": "86",
    "alternateAmountOfProductUsedInRecipeGrams": "0",
    "brewReason": "Scheduled",
    "recipeHoldVolumeMilliliters": "710",
    "timestamp": "2023-04-06T14:05:58",
    "reservoirId": "1"
  },
  "description": "Recipe Brewed",
  "id": "9b3d268b-7535-4322-b4af-eb7d8376ae2d",
  "category": "machine.telemetry",
  "type": "BrewEvent"
}
```
