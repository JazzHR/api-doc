# User Flows

## Adding a Custom Integration

**From Settings > Integrations > +Add Integrations**

![Add Integration](images/webhook/add_integration.png)

### Required for connecting a Custom Integration

* Partner Name - Unique name for this integration
* Webhook URL - URL to which JazzHR will POST
* Partner Secret - Used in hashing the JazzHR Signature header

![Connect a Custom Integration](images/webhook/connect_integration.png)

## Manual Candidate Export

**From any Candidate Profile, choose "Export Candidate"**

![Export Candidate](images/webhook/export_candidate.png)

![Export Candidate Modal](images/webhook/export_candidate_modal.png)

## Automatic Candidate Export

1\. Setup a Workflow Helper on a Workflow step

![Workflow Trigger Setup](images/webhook/workflow_trigger_setup.png)

2\. Automatically trigger a Workflow Helper when a candidate enters the Workflow step

![Workflow Trigger Export Candidate](images/webhook/workflow_trigger_export_candidate.png)
