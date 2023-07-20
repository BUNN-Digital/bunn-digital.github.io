---
title: How to Subscribe
layout: default
parent: "Event Subscriptions"
has_children: false
nav_order: 1
---

# Subscribing to Events

BUNN Digital offers the ability to subscribe to Real-Time Event reporting. This section describes how to subscribe to BUNN Events.

## Pre-requisites

1. You must have a [supported model](supported-models).
2. You must have an active BUNNlink subscription. Please see our [Registration and Support](/registration) page for more information.

## Procedure

1. Implement a REST-based [Event Consumer](event-consumer) to receive the [Standard Event Format](event-format).
   - All Events have a standard "envelope" and a variable payload. The payload will vary according to defined event types (see the [Event Catalog](/event-catalog) for supported event types). 
   - We recommend a general listener to ingest all events which then delegates to specific handlers (based on event type) for detailed processing.
2. Register your event consumer endpoint with BUNN Digital. Please reach out to your BUNNlink support contact (see [Registration and Support](/registration) if you do not know your support contact).
   - Required information is the endpoint URL and authentication details (preferably OAuth2).
   - Optionally, you may filter the events published to your event by using [tags](event-tags).
3. BUNN Digital will work with you to test your endpoint.
4. Once your endpoint is verified, your Real-Time Events will begin flowing into your endpoint!


## Supported Events

To see all currently supported events and their payloads, please review our [Event Catalog](/event-catalog).
