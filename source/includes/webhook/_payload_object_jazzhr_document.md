## JazzHR Document Object

> Sample JazzHR Document JSON Object

```json
{
   "content": "...base64encoded...",
   "mimeType": "application/pdf",
   "fileName": "TestDoc.pdf"
}
```

### Types of Documents

There are two main types of documents. One, documents that are associated to the candidate’s application / application process. These can be found in the [HR Open Candidate Object](#hr-open-candidate-object) profile’s attachments property. Two, additional documents associated directly with the candidate (and not necessarily with the candidate’s application). These will be found in the [JazzHR PersonDocuments Object](#jazzhr-persondocuments-object).

### Document URLs

Any documents in the Candidate Export Webhook payload will be included as a public URL available for 2 hours and 30 minutes after the initial candidate export event occurs.

Documents will be returned as base64 encoded content with a mime type and a file name.
