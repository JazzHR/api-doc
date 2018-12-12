## JazzHR PersonDocuments Object

> Sample JazzHR PersonDocuments JSON Object

```json
{
    "number": [
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
Note: json keys must be strings, thus the integer id is wrapped in double quotes
</aside>

### Notable Attributes

Attribute | Type | Description | Possible Answers
---------| ---- | -----
number.id.value | number | Used to key into Documents
