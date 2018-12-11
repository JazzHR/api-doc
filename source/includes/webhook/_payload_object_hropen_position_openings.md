## HROpen PositionOpenings Array

> Sample HROpen PositionOpenings JSON Object

```shell
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
                    "countryCode": null,
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
                    ],
                    "exemptIndicator": false
                }
            }
        }
    ]
}
```
