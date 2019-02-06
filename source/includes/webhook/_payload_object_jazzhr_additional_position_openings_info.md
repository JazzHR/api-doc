## JazzHR AdditionalPositionOpeningsInformation Object

> Sample JazzHR AdditionalPositionOpeningsInformation JSON Object

```json
{
    <candidate.profiles.associatedPositionOpenings.positionOpeningId.value>: {
        "isTelecommute": "string",
        "internalJobCode": "string"
    }
}

```

<aside class="notice">
Note: Each AdditionalPositionOpeningsInformation object is associated to a single item in the HR Open Candidate Object profiles array. Mapped by profiles[index].profileId.positionOpeningId.value => positionOpeningId
</aside>

<aside class="notice">
Note: Each AdditionalPositionOpeningsInformation object is also associated to a single item in the HR Open positionOpenings object. Mapped by positionOpeningId => positionProfiles.positionId.value
</aside>

### &lt;candidate.profiles.associatedPositionOpenings.positionOpeningId.value&gt;

*Id of an associatedPositionOpenings object from [HR Open Candidate Object](#hr-open-candidate-object)*
