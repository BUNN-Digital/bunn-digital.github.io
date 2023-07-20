---
title: Building an Event Consumer
layout: default
parent: "Event Subscriptions"
has_children: false
nav_order: 2
---

# Building an Event Consumer

In order to use BUNN API Events, you will need to create and register an Event Consumer. This consumer must conform to our [Standard Event Format](event-format) to ensure proper delivery. You can implement the consumer to listen/respond to events however you see fit.

## Consumer Requirements

- **Consumer must be REST-based.** <br> SOAP endpoints are not supported.
- **Consumer must support the [Standard Event Format](event-format) (JSON).**<br> This format includes a standard “envelope” for all events and a  payload that varies by event type. Please review the [Event Catalog](/event-catalog) for supported event types and payload definitions.
- **Endpoint must return a 200 OK HTTP status when the event is delivered.** <br>400-level and 500-level errors may be retried based on account settings and system availability.
- **Endpoint must be performant.** <br>BUNN recommends a non-blocking, lightweight general listener to ingest all events quickly. After acknowledging event delivery, the listener should invoke event-specific handlers (based on type) for detailed processing. This ensures your endpoint does not get bogged down in slow or blocking processing and begin to refuse connections for new events.


## Example

A simple example implementation might look like:

```
@PostMapping("/events")
@Operation(summary = "Consume Event")
public ResponseEntity consumeEvent(@RequestBody Event event) {
  log(event);
  consumeEventAsync(event);
  return new ResponseEntity<>(HttpStatus.OK);
}

@Async
public void consumeEventAsync(Event event) {
  if (TYPE_OF_INTEREST.equals(event.getType())) {
    // Event-specific processing goes here
  }
  // Default processing goes here
}
```

## Reference Implementation

We provide a [reference implementation using Java/Spring-Boot](https://github.com/BUNN-Digital/Event-Consumer-Reference-Implementation-Java).

