## HROpen Candidate Object

> Sample HROpen Candidate JSON Object

```json
{
    "documentId": {
        "value": "string",
        "schemeId": "JazzHR Candidate Export",
        "schemeAgencyId": "JazzHR"
    },
    "person": {
        "id": {
            "value": "number",
            "schemeId": "JazzHR Candidate",
            "schemeAgencyId": "JazzHR"
        },
        "name": {
            "formattedName": "string",
            "given": "string",
            "family": "string"
        },
        "gender": "string",
        "citizenShip": [
            "string"
        ],
        "communication": {
            "address": [
                {
                    "useCode": "private",
                    "countrySubdivisions": [
                        {
                            "type": "state",
                            "value": "string"
                        }
                    ],
                    "city": "string",
                    "postalCode": "string",
                    "line": "string",
                    "formattedAddress": "string"
                }
            ],
            "phone": [
                {
                    "useCode": "private",
                    "preference": 1,
                    "formattedNumber": "string"
                }
            ],
            "email": [
                {
                    "useCode": "private",
                    "preference": 1,
                    "address": "string"
                }
            ],
            "web": [
                {
                    "name": "Homepage",
                    "url": "string"
                },
                {
                    "name": "Linkedin",
                    "useCode": "business",
                    "url": "string"
                },
                {
                    "name": "Twitter",
                    "url": "string"
                }
            ]
        }
    },
    "profiles": [
        {
            "languageCode": "en-US",
            "profileId": {
                "value": "number",
                "schemeId": "JazzHR Job Application",
                "schemeAgencyId": "JazzHR"
            },
            "profileName": "Candidate Profile",
            "personAvailability": {
                "availabilityDates": [
                    {
                        "startDateTime": "date"
                    }
                ]
            },
            "associatedPositionOpenings": [
                {
                    "positionOpeningId": {
                        "value": "number",
                        "schemeId": "JazzHR Job",
                        "schemeAgencyId": "JazzHR"
                    },
                    "positionTitle": "string",
                    "positionUri": "string",
                    "candidateAppliedIndicator": true
                }
            ],
            "positionPreferences": [
                {
                    "locations": [
                        {
                            "referenceLocation": {
                                "countryCode": "string",
                                "countrySubdivisions": [
                                    {
                                        "type": "state",
                                        "value": "string"
                                    }
                                ],
                                "city": "string",
                                "postalCode": "string"
                            }
                        }
                    ],
                    "offeredRenumerationPackage": {
                        "basisCode": "Salaried",
                        "ranges": [
                            {
                                "typeCode": "BasePay",
                                "minimumAmount": {
                                    "value": "number",
                                    "currency": "USD"
                                },
                                "intervalCode": "Year"
                            }
                        ]
                    },
                    "relocation": {
                        "willingToRelocateIndicator": "boolean"
                    }
                }
            ],
            "education": [
                {
                    "educationLevelCodes": [
                        {
                            "name": "string"
                        }
                    ]
                }
            ],
            "attachments": [
                {
                    "id": {
                        "value": "number",
                        "schemeId": "JazzHR Document to Candidate",
                        "schemeAgencyId": "JazzHR"
                    },
                    "url": "string"
                }
            ]
        },
        {
            "languageCode": "en-US",
            "profileId": {
                "value": "number",
                "schemeId": "JazzHR Job Application",
                "schemeAgencyId": "JazzHR"
            },
            "profileName": "Candidate Profile",
            "personAvailability": {
                "availabilityDates": [
                    {
                        "startDateTime": "date"
                    }
                ]
            },
            "associatedPositionOpenings": [
                {
                    "positionOpeningId": {
                        "value": "number",
                        "schemeId": "JazzHR Job",
                        "schemeAgencyId": "JazzHR"
                    },
                    "positionTitle": "string",
                    "positionUri": "string",
                    "candidateAppliedIndicator": true
                }
            ],
            "positionPreferences": [
                {
                    "locations": [
                        {
                            "referenceLocation": {
                                "countryCode": "string",
                                "countrySubdivisions": [
                                    {
                                        "type": "state",
                                        "value": "string"
                                    }
                                ],
                                "city": "string",
                                "postalCode": "string"
                            }
                        }
                    ],
                    "offeredRenumerationPackage": {
                        "basisCode": "Salaried",
                        "ranges": [
                            {
                                "typeCode": "BasePay",
                                "minimumAmount": {
                                    "value": "number",
                                    "currency": "USD"
                                },
                                "intervalCode": "Year"
                            }
                        ]
                    },
                    "relocation": {
                        "willingToRelocateIndicator": "boolean"
                    }
                }
            ],
            "education": [
                {
                    "educationLevelCodes": [
                        {
                            "name": "string"
                        }
                    ]
                }
            ],
            "attachments": [
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
    ]
}

```
### Notable Attributes

Attribute | Type | Description
---------| ---- | -----
person.id.value | string | Used to key into AdditionalPersonInformation & PersonDocuments
