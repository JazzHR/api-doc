# Verification Event

During setup, the JazzHR platform will send an HTTP POST with an **empty payload** to the configured URL to determine if it has been set up correctly.

The given endpoint must respond with a status code of 200 to be considered configured correctly to receive any other webhook events from JazzHR.

HTTP POST payloads that are delivered to your webhook’s configured URL endpoint will contain a special identifying header:

Header | Description
------ | -----------
X-JazzHR-Event | Event type indicator. Header value will be `VERIFY`
