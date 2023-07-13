---
title: Event Format
layout: default
parent: "Event Subscriptions"
has_children: false
nav_order: 1
---

# Event Format

All events published by the BUNN APIs will conform to a standard format.

## Format

```
{
    "id": "00000000-0000-0000-0000-000000000000", // UUID 4
    "type": "event.type",
    "description": "Friendly Description",
    "receivedTimestampUtc": "yyyy-MM-ddTHH:mm:ss.SSSZ",
    "tags": [
        "tag1",
        "tag2"
    ],
    "category": "category",
    "payload": {
        "serialNumber": "if applicable"
        "additionalProp1": "string",
        "additionalProp2": "string",
        "additionalProp3": "string"
    }
}
```

## Example

```
{
    "id": "6ebcce83-e5c5-456c-9e18-b446b070502c",
    "type": "recipe.dispensed",
    "description": "Recipe Dispensed - Non Portion Controlled",
    "receivedTimestampUtc": "2023-01-01T22:40:03.265086400Z",
    "tags": [
        "machine",
        "telemetry"
    ],
    "category": "machine.telemetry",
    "payload": {
        "serialNumber": "EP00005696",
        "timestamp": "2023-01-01T17:38:43",
        "tapId": 3,
        "reservoirId": 3,
        "tapAvailability": "Not Available",
        "recipeAgeAtTimeOfDispenseMinutes": 61,
        "recipeTemperatureCelcius": 84,
        "volumeDispensedMilliliters": 276,
        "tapActiveDurationMilliseconds": 6429,
        "recipeNameInfo": "REGULAR"
    }
}
```

## Details

| Field                   | Type   | Example                              | Description                                         |
|:------------------------|:-------| :----------------------------------- | :-------------------------------------------------- |
| id                      | String | "00000000-0000-0000-0000-000000000000" | Unique ID generated for each instance of an event. Generated using UUID 4 (Random). <br><br>More details can be found on [Wikipedia](https://en.wikipedia.org/wiki/Universally_unique_identifier#Version_4_(random)) and/or the [IETF Specification](https://www.ietf.org/rfc/rfc4122.txt). |
| type                    | String | "recipe.brewed" | This is the "kind" of event that was published and corresponds to an event definition in our [Event Catalog](/event-catalog). |
| description             | String | "This event describes a brew operation on a machine." | A brief, human-readable description of the event type. Corresponds to descriptions found in our [Event Catalog](/event-catalog). |
| receivedTimestampUtc    | String | "1970-01-01T00:00:00.000000000Z" | The data and time that the event was recieved by the event-processing system. <br><br>Conforms to [ISO-8601](https://en.wikipedia.org/wiki/ISO_8601) in [Coordinated Universal Time (UTC)](https://en.wikipedia.org/wiki/Coordinated_Universal_Time). |
| category (deprecated) | String | "machine.alarm" | Deprecated. Will be replaced with tags. <br><br> Category describes a hierarchical grouping for this event that is used for filtering when searching or publishing to your [Event Consumer](event-consumer).  |
| tags                    | String Array | ["alarm", "fault"] | Tags describe one or more ways to group like events. These can be used to filter events when searching or publishing to your [Event Consumer](event-consumer). <br><br>More information can be found in our [Event Tags](event-tags) documentation. |
| payload                 | JSON | { "active": false } | The payload holds the custom data elements for each event. The format for each event type can be found in our [Event Catalog](/event-catalog). <br><br>Conforms to the [JSON specification](https://www.json.org/json-en.html). |
