## JazzHR AdditionalPersonInformation Object

> Sample JazzHR AdditionalPersonInformation JSON Object

```shell
{
    "number": {
        "isTelecommute": "string",
        "internalJobCode": "string"
    }
}

```

### Notes
A single AdditionalPersonInformation object maps to the single HROpen Candidate Object person property. Mapped by person->id->value => personId.

JSON keys must be strings, thus the integer id is wrapped in double quotes.
