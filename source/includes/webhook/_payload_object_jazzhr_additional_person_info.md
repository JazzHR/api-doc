## JazzHR AdditionalPersonInformation Object

> Sample JazzHR AdditionalPersonInformation JSON Object

```json
{
    "number": {
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

### Notes
A single AdditionalPersonInformation object maps to the single HROpen Candidate Object person property. Mapped by person->id->value => personId.

JSON keys must be strings, thus the integer id is wrapped in double quotes.

### Notable Attributes

Attribute | Type | Description | Possible Answers
---------| ---- | -----
number.flightGrade | string | Pilot flight grade | "No Answer", "Student Pilot", "Recreational Pilot", "Private Pilot", "Commercial Pilot", "Airline Transport Pilot"
number.eeoRace | string | EEO race options | "Decline to answer", "Hispanic or Latino", "White, not Hispanic or Latino", "Black or African-American, not Hispanic or Latino", "Asian, not Hispanic or Latino", "Native Hawaiian or Other Pacific Islander, not Hispanic or Latino", "American Indian or Alaskan Native, not Hispanic or Latino", "Two or More Races, not Hispanic or Latino"
number.eeoDisability | string | EEO disability options | "Disabled Veteran", "Special Disabled Veteran", "Vietnam Era Veteran", "3 Yr. Recently Separated Veteran", "1 Yr. Recently Separated Veteran", "Other Protected Veteran", "Disabled Individual", "Not applicable"
number.eeoVeteran | string | EEOC veteran classification | "I identify as one or more of the classifications of protected veteran listed above", "I am not a protected veteran"