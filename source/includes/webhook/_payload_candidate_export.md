# Candidate Export Payload

> Sample JSON Payload

```json
{
    "candidate": {
        //<HROpen Candidate>
    },
    "positionOpenings": [
        //<HROpen PositionOpenings>
    ],
    "personDocuments": {
        //<JazzHR PersonDocuments>
    },
    "additionalPersonInformation": {
        //<JazzHR AdditionalPersonInformation>
    },
    "additionalProfileInformation": {
        //<JazzHR AdditionalPositionOpeningsInformation>
    },
    "additionalPositionOpeningsInformation": {
        //<JazzHR AdditionalProfileInformation>
    }
}
```

This is a sample of the JazzHR Candidate Export Webhook JSON payload. Listed here
are all properties linked to their corresponding objects.

Property | Type
-------- | ----
candidate | [HROpen Candidate](#hropen-candidate-object)
positionOpenings | HROpen PositionOpenings
additionalPersonInformation | JazzHR AdditionalPersonInformation
additionalPositionOpeningsInformation | JazzHR AdditionalPositionOpeningsInformation
additionalProfileInformation | JazzHR AdditionalProfileInformation

A full JSON example can be downloaded [here](files/jazzhr_candidate_export.sample.json).
