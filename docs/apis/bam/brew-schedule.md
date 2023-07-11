---
title: "Usage: Brew Schedule"
layout: default
parent: "BUNN Asset Management API"
grand_parent: "BUNN APIs"
has_children: false
nav_order: 3
---

# How to push a Brew Schedule

## Prerequisites

- Your account has a current BUNNlink subscription
- You have current API credential (Auth0)
- The machine to configure is a Bean-to-Batch machine
- The machine to configure is actively connected to BUNNlink
- The machine is running software at v## or later

## Procedure

1. Prepare the Brewing Schedule in accordance with the [Brew Schedule Format](brew-schedule-format).
2. Execute a POST request to [https://api.bunn.com/bunn-asset-management/v0/asset-configuration/brewing-schedule](https://api.bunn.com/bunn-asset-management/v0/asset-configuration/brewing-schedule). See [Swagger Documentation](https://api.bunn.com/bunn-asset-management/swagger-ui/) for details.
3. [Monitor transfer status](monitoring-transfers) in BUNNlink portal

## Notes

- Correlation ID on header is used for ??
- External ID in payload is used for ??

## Asynchronous Responses (Events)

- Success: [Configuration Applied](#)
- Errors:
  - 
  - Machine Offline: [Machine Offline Event](#)
  - Communication error: [Communication Error](#)

## References
- BUNN Asset Management API [Swagger Documentation](https://api.bunn.com/bunn-asset-management/swagger-ui/) 
- Brew Schedule File Format
