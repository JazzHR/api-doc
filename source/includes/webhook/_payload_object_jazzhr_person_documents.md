## JazzHR PersonDocuments Object

> Sample JazzHR PersonDocuments JSON Object

```json
{
    <candidate.person.id.value>: [
        {
            "id": {
                "value": "number",
                "schemeId": "JazzHR Document to Candidate",
                "schemeAgencyId": "JazzHR"
            },
            "url": "string"
        }
    ]
}
```

<aside class="notice">
Note: A single PersonDocuments object maps to the single HROpen Candidate Object person property. Mapped by person.id.value => personId.
</aside>

<aside class="notice">
Note: JSON keys must be strings, thus the integer id is wrapped in double quotes
</aside>

<aside class="notice">
Note: See <a href="#jazzhr-document-object">JazzHR Document Object</a> section for more information on documents.
</aside>

### &lt;candidate.person.id.value&gt;

*Id of the candidate's person object from [HROpen Candidate Object](#hropen-candidate-object)*
