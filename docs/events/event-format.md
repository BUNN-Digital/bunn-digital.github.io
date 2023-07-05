---
title: Event Format
layout: default
parent: Events
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
    "tags": [
        "tag1",
        "tag2"
    ],
    "description": "Friendly Description",
    "receivedTimestampUtc": "yyyy-MM-ddTHH:mm:ss.SSSZ",
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
```

## Details

| Field | Type   | Example                              | Description                                         |
| :-----|:-------| :----------------------------------- | :-------------------------------------------------- |
| id    | String | "00000000-0000-0000-0000-000000000000" | Unique ID generated for each instance of an event. Generated using UUID 4 (Random). More details can be found on [Wikipedia](https://en.wikipedia.org/wiki/Universally_unique_identifier#Version_4_(random)) and/or the [IETF Specification](https://www.ietf.org/rfc/rfc4122.txt). |
| type  | String | "recipe.brewed" | This is the "kind" of event that was published and corresponds to an event definition in our [Event Catalog](..). |
| tags  | String Array | ["alarm", "fault"] | Tags describe one or more ways to group like events. These can be used to filter events when searching or publishing to your [Event Consumer](event-consumer). More information can be found in our [Event Tags](event-tags) documentation. |
| description  | String | "This event describes a brew operation on a machine." | A brief, human-readable description of the event type. Corresponds to descriptions found in our [Event Catalog](..). |
| receivedTimestampUtc  | String | "1970-01-01T00:00:00.000000000Z" | The data and time that the event was recieved by the event-processing system. Conforms to [ISO-8601](https://en.wikipedia.org/wiki/ISO_8601) in [Coordinated Universal Time (UTC)](https://en.wikipedia.org/wiki/Coordinated_Universal_Time). |
| payload  | JSON | { "active": false } | The payload holds the custom data elements for each event. The format for each event type can be found in our [Event Catalog](..). Conforms to the [JSON specification](https://www.json.org/json-en.html). |
