---
title: Event Tags
layout: default
parent: "Event Subscriptions"
has_children: false
nav_order: 4
---

# Event Tags

Tags are a means to describe and group events. They may be used in several contexts, such as selectors in a UI or filters in an API.

## Tag Listing

| Tag       | Description                                                                   |
| :-------- | :---------------------------------------------------------------------------- |
| admin     | Indicates the event pertains to an administrative activity.                   |
| alarm     | Indicates an urgent notification, typically requiring operator intervention.  |
| fault     | Indicates a mechanical or electrical failure on a device.                     |
| machine   | Indicates the event pertains to a particular BUNN device. Typically the device is identified with a serial number in the payload.            |
| telemetry | Indicates an event is reporting information during normal operation.          |
