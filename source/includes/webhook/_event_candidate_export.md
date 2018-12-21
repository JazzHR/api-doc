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

HTTP POST payloads that are delivered to your webhook’s configured URL endpoint will contain specific headers:

Header | Description
------ | -----------
Link | This header will contain the URL for the candidate’s profile within JazzHR.
X-JazzHR-Event | Event type indicator. Header value will be `CANDIDATE-EXPORT`
X-JazzHR-Signature | The HMAC hex digest of the response body used to verify the source of the webhook payload.<br/><br/>The HMAC hex digest is generated using the `sha256` hash function and the `secret` provided to JazzHR as the HMAC key.

## URL Requirements

> Example URL suggestions

```shell

https://example.service/webhook/{{clientId}}

https://example.service/webhook?id={{clientId}}
```

In situations where the service receiving a webhook from JazzHR is serving multiple clients, we are requiring the URL provided to include a unique identifier.

In the examples provided, the `{{clientId}}` placehold is for an identifier originating from your system. This identifier will be how the receiving system can differentiate to whom the incoming data belongs to.
