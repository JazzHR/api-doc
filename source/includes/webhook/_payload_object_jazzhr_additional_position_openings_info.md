## JazzHR AdditionalPositionOpeningsInformation Object

> Sample JazzHR AdditionalPositionOpeningsInformation JSON Object

```json
{
    "number": {
        "isTelecommute": "string",
        "internalJobCode": "string"
    }
}

```

<aside class="notice">
Note: Each AdditionalPositionOpeningsInformation object is associated to a single item in the HROpen Candidate Object profiles array. Mapped by profiles[index].profileId.positionOpeningId.value => positionOpeningId
</aside>

<aside class="notice">
Note: Each AdditionalPositionOpeningsInformation object is also associated to a single item in the HROpen positionOpenings object. Mapped by positionOpeningId => positionProfiles.positionId.value
</aside>
