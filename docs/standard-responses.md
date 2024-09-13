---
title: API Responses and Error Codes
layout: home
has_children: false
nav_order: 4
---

# Standard API Responses and Error Codes

This section describes standard responses and error codes as currently returned by the BUNN Digital APIs.

## Valid Responses

| HTTP Code                    | Description                  |
| :--------------------------- | :--------------------------- |
| 200 OK                       | Request Succeeded            |
| 201 Created                  | Artifact Created             |
| 202 Accepted                 | Artifact Accepted            |
| 204 No Content               | No Results Found for Request |
| 208 Already Reported         | Artifact Already Exists      |


## Error Responses

| HTTP Code                    | Error Code                      | Description                                         |
| :--------------------------- | :------------------------------ | :-------------------------------------------------- |
| 400 Bad Request              |                                 |                                                     |
| 401 Unauthorized             | request.requires-authentication | Authentication required                             |
| 403 Forbidden                | request.unauthorized            | Insufficient authorization to complete this request |
| 404 Not Found                | N/A                             | Unknown page / endpoint                             |
|                              | N/A                             | Suspicous request                                   |
|                              | request.unknown-resource        | Requested operation resource is not available       |
| 405 Method Not Allowed       |                                 |                                                     |
| 406 Not Acceptable           |                                 |                                                     |
| 408 Request Timeout          |                                 |                                                     |
| 409 Conflict                 | request.parameter.exists        |                                                     |
| 420 Enhance Your Calm        | request.rate-exceeds-threshold  | Request exceeds rate limits                         |
| 422 Unprocessable Entity     | request.parameter.required      | A required input was not provided for a request     |
|                              | request.parameter.invalid       | Validation errors or invalid input on a request     |
| 423 Locked                   |                                 |                                                     |
| 429 Too Many Requests        | request.rate-exceeds-threshold  | Request exceeds rate limits                         |
| 500 Internal Server Error    | error.internal                  | Internal Error                                      |
| 501 Not Implemented          |                                 |                                                     |
| 503 Service Unavailable      |                                 |                                                     |
| 507 Insufficient Storage     |                                 |                                                     |
| 509 Bandwidth Limit Exceeded |                                 |                                                     |
