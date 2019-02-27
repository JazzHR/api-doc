## HROpen Candidate Object

> Sample HROpen Candidate JSON Object

```json
{
    "person": {
      "id": {
        "value": "string",
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
      "applyDate": "date",
      "communication": {
        "address": [{
          "countrySubdivisions": [{
            "type": "state",
            "value": "string"
          }],
          "city": "string",
          "postalCode": "string",
          "line": "string",
          "formattedAddress": "string"
        }],
        "phone": [{
          "formattedNumber": "string"
        }],
        "email": [{
          "address": "string"
        }],
        "web": "template"
      }
    },
    "profiles": [{
      "languageCode": "en-US",
      "profileId": {
        "value": "string",
        "schemeId": "JazzHR Job Application",
        "schemeAgencyId": "JazzHR"
      },
      "associatedPositionOpenings": [{
        "positionOpeningId": {
          "value": "string",
          "schemeId": "JazzHR Job",
          "schemeAgencyId": "JazzHR"
        },
        "positionTitle": "string",
        "positionUri": "string",
        "candidateStatus": {
          "name": "string",
          "category": "string",
          "transitionDateTime": "datetime"
        }
      }],
      "education": [{
        "educationLevelCodes": [{
          "name": "string"
        }]
      }],
      "attachments": [{
        "id": {
          "value": "number",
          "schemeId": "JazzHR Document to Candidate",
          "schemeAgencyId": "JazzHR"
        },
        "descriptions": [
          "string"
        ],
        "url": "string"
      }]
    }]
  }
}

```

### person.id.value

*Used to key into AdditionalPersonInformation & PersonDocuments*

### person.gender

*Prospect's gender*

Possible Values:

- "Male"
- "Female"

### person.citizenship

*Prospect work authorization*

Possible Values:

- "No Answer"
- "U.S. Citizen/Permanent Resident"
- "Non-citizen allowed to work for any employer"
- "Non-citizen allowed to work for current employer"
- "Non-citizen seeking work authorization"
- "Canadian Citizen/Permanent Resident"
- "Other"

### profiles.associatedPositionOpenings.positionOpeningId.value

*Used to key into PositionOpenings*

### profiles.associatedPositionOpenings.candidateStatus

The candidate's status in the hiring workflow. Possible values for `category` include:

- New
- Active
- Hired
- Not Hired

### profiles.education.educationLevelCodes.name

*Education level*

Possible Values:

- "No Answer"
- "GED or Equivalent"
- "High School"
- "Some College"
- "College - Associates"
- "College - Bachelor of Arts"
- "College - Bachelor of Fine Arts"
- "College - Bachelor of Science"
- "College - Master of Arts"
- "College - Master of Science"
- "College - Master of Fine Arts"
- "College - Master of Business Administration"
- "College - Doctorate"
- "Medical Doctor"
- "Other"
