---
title: "Usage: Brew Schedule"
layout: default
parent: "BUNN Asset Management API"
grand_parent: "BUNN APIs"
has_children: false
nav_order: 3
---

# Pushing a Brew Schedule

Brew Schedules allow customers to set hold volumes and other settings for specific recipes at specific time ranges over a week. These settings allow customers to optimize availability and minimize waste.

## Prerequisites

- Your account has a current BUNNlink subscription
- You have current API credentials (Auth0)
- The machine to configure is a Bean-to-Batch machine
- The machine to configure is actively connected to BUNNlink
- The machine is running software at version 00.34 or later

## Procedure

1. Prepare the Brewing Schedule in accordance with the [Brew Schedule Format](brew-schedule-format).
2. Execute a POST request to [https://api.bunn.com/bunn-asset-management/v0/asset-configuration/brewing-schedule](https://api.bunn.com/bunn-asset-management/v0/asset-configuration/brewing-schedule). See [Swagger Documentation](https://api.bunn.com/bunn-asset-management/swagger-ui/) for details.
3. [Monitor transfer status](monitoring-transfers) in BUNNlink portal.

## Notes

- Correlation ID on header is used for to continue transaction tracking from a user's system. The correlation ID passed in will be returned on the API response (as the same header).
- Sometimes the request may time-out while the file transfer is being prepared. This does not mean that the request failed. Please monitor via BUNNlink portal. This issue will be fixed in a future release.

## Asynchronous Responses (Events)

Event-driven responses will be available in a future enhancement. For now, please [monitor your file transfer in BUNNlink Portal](monitoring-transfers).

## References
- BUNN Asset Management API [Swagger Documentation](https://api.bunn.com/bunn-asset-management/swagger-ui/) 
- [Brew Schedule File Format](brew-schedule-format)
