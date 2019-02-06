## JazzHR AdditionalProfileInformation Object

> Sample JazzHR AdditionalProfileInformation JSON Object

```json
{
    <candidate.profiles.profileId.value>: {
        "candidateApplyDate": "date",
        "rating": "number",
        "workflowStatus": "string",
        "workflowStatusCategory": "string",
        "workflowDispositionDatetime": "datetime"
    }
}

```

<aside class="notice">
Note: Multiple AdditionalProfileInformation objects which map to a single item in the HR Open Candidate Object profiles array. Mapped by profiles[index].associatedPositionOpenings.value => profileId
</aside>

<aside class="notice">
Note: json keys must be strings, thus the integer id is wrapped in double quotes
</aside>

### &lt;candidate.profiles.profileId.value&gt;

*Id of a profile object from [HR Open Candidate Object](#hr-open-candidate-object)*

### workflowStatusCategory

*Category of step in the related workflow*

Possible Values:

- "Active"
- "Hired"
- "Not Hired"
