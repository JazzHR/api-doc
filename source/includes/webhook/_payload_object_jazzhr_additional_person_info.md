## JazzHR AdditionalPersonInformation Object

> Sample JazzHR AdditionalPersonInformation JSON Object

```json
{
    <candidate.person.id.value>: {
        "languagesSpoken": "string",
        "referrer": "string",
        "wmyu": "string",
        "license": "boolean",
        "commercialDriversLicense": "boolean",
        "canWorkWeekends": "boolean",
        "canWorkEvenings": "boolean",
        "overEighteen": "boolean",
        "flightHours": "number",
        "flightGrade": "string",
        "canWorkOvertime": "boolean",
        "felony": "boolean",
        "felonyExplanation": "string",
        "gpa": "string",
        "references": "string",
        "eeoRace": "string",
        "eeoDisability": "string",
        "eeoVeteran": "string"
    }
}

```
<aside class="notice">
A single AdditionalPersonInformation object maps to the single HROpen Candidate Object person property. Mapped by person.id.value => personId.
</aside>
<aside class="notice">
JSON keys must be strings, thus the integer id is wrapped in double quotes.
</aside>

### &lt;candidate.person.id.value&gt;

*Id of the candidate's person object from [HROpen Candidate Object](#hropen-candidate-object)*

### flightGrade

*Pilot flight grade*

Possible Values:

- "No Answer"
- "Student Pilot"
- "Recreational Pilot"
- "Private Pilot"
- "Commercial Pilot"
- "Airline Transport Pilot"

### eeoRace

*EEO race options*

Possible Values:

- "Decline to answer"
- "Hispanic or Latino"
- "White, not Hispanic or Latino"
- "Black or African-American, not Hispanic or Latino"
- "Asian, not Hispanic or Latino"
- "Native Hawaiian or Other Pacific Islander, not Hispanic or Latino"
- "American Indian or Alaskan Native, not Hispanic or Latino"
- "Two or More Races, not Hispanic or Latino"

### eeoDisability

*EEO disability options*

Possible Values:

- "Disabled Veteran"
- "Special Disabled Veteran"
- "Vietnam Era Veteran"
- "3 Yr. Recently Separated Veteran"
- "1 Yr. Recently Separated Veteran"
- "Other Protected Veteran"
- "Disabled Individual"
- "Not applicable"

### eeoVeteran

*EEOC veteran classification*

Possible Values:

- "I identify as one or more of the classifications of protected veteran listed above"
- "I am not a protected veteran"
