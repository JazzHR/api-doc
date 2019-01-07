# User Flows

## Adding a Custom Integration

**From Settings > Integrations**

Select the `Add Custom Integration` button to open the connection modal.

![Add Integration](images/webhook/add_integration.png)

### Required for connecting a Custom Integration

Information required to setup a custom integration:

* **Integration Name** - Unique name for this integration
* **Integration [Webhook] URL** - URL to which JazzHR will POST
* **Secret Key** - Used in hashing the JazzHR Signature header, optional value depending on the partner.

![Connect a Custom Integration](images/webhook/connect_integration.png)

When the `Save` button is clicked, the [Verification Event](#verification-event) will be sent to the provided endpoint before it is finalized.

### Connected Custom Integration

Once the saving has completed, the Custom Integration will be displayed in the setup state. Options are available to edit information or remove the integration.

![Connected Custom Integration](images/webhook/connect_integration_saved.png)

## Manual Candidate Export

**From any Candidate Profile, choose "Export Candidate"**

![Export Candidate](images/webhook/export_candidate.png)

![Export Candidate Modal](images/webhook/export_candidate_modal.png)

## Automatic Candidate Export

1\. Setup a Workflow Helper on a Workflow step

![Workflow Trigger Setup](images/webhook/workflow_trigger_setup.png)

2\. Automatically trigger a Workflow Helper when a candidate enters the Workflow step

![Workflow Trigger Export Candidate](images/webhook/workflow_trigger_export_candidate.png)
