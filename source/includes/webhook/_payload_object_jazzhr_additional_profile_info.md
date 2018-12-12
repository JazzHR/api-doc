## JazzHR AdditionalProfileInformation Object

> Sample JazzHR AdditionalProfileInformation JSON Object

```json
{
    "number": {
        "rating": "number",
        "workflowStatus": "string",
        "workflowStatusCategory": "string",
        "workflowDispositionDatetime": "datetime"
    }
}

```

<aside class="notice">
Note: Multiple AdditionalProfileInformation objects which map to a single item in the HROpen Candidate Object profiles array. Mapped by profiles[index]->associatedPositionOpenings->value => profileId
</aside>

<aside class="notice">
Note: json keys must be strings, thus the integer id is wrapped in double quotes
</aside>
