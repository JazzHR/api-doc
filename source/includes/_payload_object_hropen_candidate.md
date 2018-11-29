## HROpen Candidate Object

> Sample HROpen Candidate JSON Object

```shell
{
        "documentId": {
            "value": "39393_204_<timestamp>",
            "schemeId": "JazzHR Candidate Export",
            "schemeAgencyId": "JazzHR"
        },
        "person": {
            "id": {
                "value": "3456291",
                "schemeId": "JazzHR Candidate",
                "schemeAgencyId": "JazzHr"
            },
            "name": {
                "formattedName": "Test Candidate",
                "given": "Test",
                "family": "Candidate"
            },
            "gender": "No Answer",
            "citizenShip": ["No Answer"],
            "communication": {
                "address": [
                    {
                        "useCode": "private",
                        "countryCode": null,
                        "countrySubdivisions": [
                            {
                                "type": "state",
                                "value": "PA"
                            }
                        ],
                        "city": "Pittsburgh",
                        "postalCode": "15212",
                        "line": "123 Walnut Street",
                        "formattedAddress": "100 Walnut Street Pittsburgh PA 15212"
                    }
                ],
                "phone": [
                    {
                        "useCode": "private",
                        "preference": 1,
                        "formattedNumber": "1234567890"
                    }
                ],
                "email": [
                    {
                        "useCode": "private",
                        "preference": 1,
                        "address": "test.candidate@jazzhr.com"
                    }
                ],
                "web": [
                    {
                        "name": "Homepage",
                        "url": null
                    },
                    {
                        "name": "Linkedin",
                        "useCode": "business",
                        "url": null
                    },
                    {
                        "name": "Twitter",
                        "url": null
                    }
                ]
            }
        },
        "profiles": [
            {
                "languageCode": "en-US",
                "profileId": {
                    "value": "934839",
                    "schemeId": "JazzHR Job Application",
                    "schemeAgencyId": "JazzHR"

                },
                "profileName": "Candidate Profile",
                "personAvailability": {
                    "availabilityDates": [
                        {
                            "startDateTime": null,
                            "endDateTime": null
                        }
                    ]
                },
                "associatedPositionOpenings": [
                    {
                        "positionOpeningId": {
                            "value": 31539,
                            "schemeId": "JazzHR Job",
                            "schemeAgencyId": "JazzHR"
                        },
                        "positionTitle": "Test Job",
                        "positionUri":"a.co/apply/Yxbs70xdRG/Test-Job",
                        "candidateAppliedIndicator": true
                    }
                ],
                "employerPreferences": [],
                "positionPreferences":
                        [{
                           "locations": [
                              {
                                "referenceLocation": {
                                    "countryCode": "United States",
                                    "countrySubdivisions": [
                                        {
                                            "type": "state",
                                            "value": "(Multiple States)"
                                        }
                                    ],
                                    "city": null,
                                    "postalCode": null
                                }
                        }],
                        "jobCategories": [],
                        "positionTitles": [],
                        "positionOfferingTypeCodes": [],
                        "positionScheduleTypeCodes": [],
                        "careerLevelCodes": [],
                        "offeredRenumerationPackage": {
                            "basisCode": "Salaried",
                            "ranges": [
                                {
                                    "typeCode": "BasePay",
                                    "minimumAmount": {
                                        "value": 50000,
                                        "currency": "USD"
                                    },
                                    "intervalCode": "Year"
                                }
                            ]
                        },
                        "relocation": {
                            "willingToRelocateIndicator": false
                        },
                        "workingLanguageCodes": [

                        ]
                    }
                ],
                "employment": [],
                "education": [
                    {
                        "educationLevelCodes": [
                            {
                                "name": "No Answer"
                            }
                        ]
                    }
                ],
                "attachments": []
            }
      ]
}

```
Property | Type
-------- | ------
documentId | [HROpen Candidate ID Object](#documentid)
person | [HROpen Person Object](#person)
profiles | HROpen Profiles Array

### documentId
Property | Type | Value
---------| ---- | -----
value | string | Unique ID
schemeId | string | "JazzHR Candidate Export"
schemeAgencyId | string | "JazzHR"

### person

### person#id

Property | Type | Value
---------| ---- | -----
value | string | Unique ID
schemeId | string | "JazzHR Candidate"
schemeAgencyId | string | "JazzHR"
