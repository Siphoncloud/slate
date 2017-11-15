# Errors

The Siphon API uses the following error codes:


Error Code | Meaning | Description
---------- | ------- | -----------
400 | Bad Request | Your request is malformed.
401 | Unauthorized | Your API credentials are wrong.
402 | Payment Required | Your account does not have an active subscription
404 | Not Found | Your request is trying to access an unknown endpoint.
405 | Method Not Allowed | You tried to access an end point with an invalid method.
406 | Not Acceptable | You requested a format that is not json.
500 | Internal Server Error | We had a problem with our server. Try again later.
503 | Service Unavailable | We're temporarily offline for maintenance. Please try again later.
