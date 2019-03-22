# Verification Event

During setup, the JazzHR platform will send an HTTP POST to the configured URL to determine if it has been set up correctly. The request body will always match the following JSON:

`{"data": "JazzHR Verify Event"}`

The given endpoint must respond with a status code of 200 to be considered configured correctly to receive any other webhook events from JazzHR.

HTTP POST payloads that are delivered to your webhook’s configured URL endpoint will contain two special headers:

Header | Description
------ | -----------
X-JazzHR-Event | Event type indicator. Header value will be `VERIFY`.
X-JazzHR-Signature | The HMAC hex digest of the response body used to verify the source of the webhook payload.<br/><br/>The HMAC hex digest is generated using the `sha256` hash function and the `secret` provided to JazzHR as the HMAC key.
