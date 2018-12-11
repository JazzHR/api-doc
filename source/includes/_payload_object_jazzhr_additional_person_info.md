## JazzHR AdditionalPersonInformation Object

> Sample JazzHR AdditionalPersonInformation JSON Object

```shell
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
