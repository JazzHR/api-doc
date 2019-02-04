## HR Open PositionOpenings Array

> Sample HR Open PositionOpenings Array

```json
[
    {
        "documentId": {
            "value": "string",
            "schemeId": "JazzHR Candidate Export",
            "schemeAgencyId": "JazzHR"
        },
        "language": "en-US",
        "statusCode": "string",
        "approvalStatusCode": "string",
        "positionProfiles": [
            {
                "positionId": {
                    "value": "number",
                    "schemeId": "JazzHR Job",
                    "schemeAgencyId": "JazzHR"
                },
                "profileName": "Job Posting",
                "language": "en-US",
                "postingInstructions": [
                    {
                        "channelId": {
                            "value": "internal"
                        },
                        "start": "date",
                        "end": "date",
                        "applicationMethods": [
                            {
                                "personContact": {
                                    "name": {
                                        "given": "string",
                                        "family": "string"
                                    },
                                    "roleCode": "Hiring Manager",
                                    "communication": {
                                        "email": [
                                            {
                                                "address": "string"
                                            }
                                        ],
                                        "phone": [
                                            {
                                                "formattedNumber": "string"
                                            }
                                        ]
                                    },
                                    "primaryLanguage": "en-US"
                                },
                                "applicationUri": {
                                    "url": "string"
                                }
                            }
                        ]
                    }
                ],
                "positionTitle": "string",
                "positionLocation": [
                    {
                        "city": "string",
                        "postalCode": "string",
                        "countrySubDivisions": [
                            {
                                "type": "state",
                                "value": "string"
                            }
                        ]
                    }
                ],
                "positionOrganizations": [
                    {
                        "name": "string",
                        "responsibilityCode": "Department"
                    }
                ],
                "positionOpenQuantity": 1,
                "jobCategories": [
                    {
                        "code": "string"
                    }
                ],
                "careerLevels": [
                    {
                        "code": "string"
                    }
                ],
                "positionFormattedDescriptions": [
                    {
                        "title": "Job Description",
                        "content": "template"
                    }
                ],
                "positionScheduleTypeCodes": [
                    "string"
                ],
                "offeredRemunerationPackage": {
                    "basisCode": "Salaried",
                    "ranges": [
                        {
                            "intervalCode": "Year",
                            "referenceAmount": {
                                "value": "number",
                                "currency": "USD"
                            },
                            "typeCode": "Minimum BasePay"
                        },
                        {
                            "intervalCode": "Year",
                            "referenceAmount": {
                                "value": "number",
                                "currency": "USD"
                            },
                            "typeCode": "Maximum BasePay"
                        }
                    ]
                },
                "positionClassification": {
                    "USPositionClassification": {
                        "EEOCJobCategoryCodes": [
                            "string"
                        ]
                    }
                }
            }
        ]
    }
]
```

<aside class="notice">
Note: Each PositionOpening object is associated to a single item in the HR Open Candidate Object profiles array. Mapped by profiles[index].profileId.positionOpeningId.value => positionProfiles->positionId->value
</aside>

<aside class="notice">
Note: Each PositionOpening object is also associated to a single item in the JazzHR AdditionalPositionOpeningsInformation object. Mapped by positionOpeningId => positionProfiles.positionId.value
</aside>

### approvalStatusCode

*Job's approval status*

Possible Values:

- "Needs to be Approved"
- "Approved"
- "Not Approved"

### positionProfiles.jobCategories.code

*Job's eeo cateogry*

Possible Values:

- "No Selection"
- "Executive/Senior Level Officials and Managers"
- "Professionals"
- "Technicians"
- "Sales Workers"
- "Administrative Support Workers"
- "Craft Workers"
- "Operatives"
- "Laborers and Helpers"
- "Service Workers"
- "First/Mid Level Officals & Managers"

### positionProfiles.careerLevels.code

*Minimum required experience level*

Possible Values:

- "Not Specified"
- "Student (High School)"
- "Student (College)"
- "Entry Level"
- "Mid Level",
- "Experienced"
- "Manager/Supervisor"
- "Senior Manager/Supervisor"
- "Executive"
- "Senior Executive"

### positionProfiles.positionScheduleTypeCodes

*Employment type*

Possible Values:

- "Not Specificed"
- "Full Time"
- "Part Time"
- "Part Time to Full Time"
- "Temporary"
- "Temporary to Full Time"
- "Contracted"
- "Contracted to Full Time"
- "Internship"
- "Internship to Full Time"
- "Seasonal"
- "Volunteer"

### positionProfiles.positionClassification.USPositionClassification.EEOCJobCategoryCodes

*Job's EEOC category classification*

Possible Values:

- "No Selection"
- "Executive/Senior Level Officials and Managers"
- "Professionals"
- "Technicians"
- "Sales Workers"
- "Administrative Support Workers"
- "Craft Workers"
- "Operatives"
- "Laborers and Helpers"
- "Service Workers"
- "First/Mid Level Officals & Managers"
