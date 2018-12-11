# Candidate Export Event

## Overview

This is the official documentation for the JazzHR Candidate Export Webhook.

The Candidate Export Webhook allows partners to build custom endpoints and subscribe
to export events that happen via manual or automatic user actions within the JazzHR platform.
When a candidate export is triggered, we will send an HTTP POST payload to the configured URL.
The Candidate Export Event payload will be sent via HTTP POST to the configured URL endpoint.

To acknowledge receipt of a webhook, your endpoint should return a `2xx` HTTP status code.

All response codes outside of this range, including `3xx` codes, will indicate that
you did not receive the webhook, and attempts will be made to redeliver the data
*every 5 minutes for up to 2 hours*. Webhook data is sent as JSON in the POST request body.

## Delivery Headers

HTTP POST payloads that are delivered to your webhook’s configured URL endpoint will contain a special header:

Header | Description
------ | -----------
Link | This header will contain the URL for the candidate’s profile within JazzHR.
X-JazzHR-Signature | The HMAC hex digest of the response body used to verify the source of the webhook payload. The HMAC hex digest is generated using the `sha256` hash function and the `secret` provided to JazzHR as the HMAC key.
