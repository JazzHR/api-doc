## JazzHR AdditionalPersonInformation Object

> Sample JazzHR AdditionalPersonInformation JSON Object

```shell
{
    "3456291": {
        "languagesSpoken": <string>,
        "referer": <string>,
        "wmyu": <string>,
        "license": <boolean>,
        "commericalDriversLicense": <boolean>,
        "canWorkWeekends": <boolean>,
        "canWorkEvenings": <boolean>,
        "over18": <boolean>,
        "flightHours": <integer>,
        "flightGrade": <boolean>,
        "canWorkOvertime": <boolean>,
        "felony": <boolean>,
        "felonyExplanation": <string>,
        "gpa": <string>,
        "references": <string>,
        "eeoRace": <string>,
        "eeoDisability": <string>,
        "eeoVeteran": <string>
    }
}

```

### Notes
A single AdditionalPersonInformation object maps to the single HROpen Candidate Object person property. Mapped by person->id->value => personId.

JSON keys must be strings, thus the integer id is wrapped in double quotes.
