# Candidate Export Payload

> Sample JSON Payload

```json
{
    "candidate": {
        //<HR Open Candidate>
    },
    "positionOpenings": [
        //<HR Open PositionOpenings>
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
candidate | [HR Open Candidate](#hropen-candidate-object)
positionOpenings | [HR Open PositionOpenings Array](#hropen-positionopenings-array)
personDocuments | [JazzHR PersonDocuments Object](#jazzhr-persondocuments-object)
additionalPersonInformation | [JazzHR AdditionalPersonInformation](#jazzhr-additionalpersoninformation-object)
additionalPositionOpeningsInformation | [JazzHR AdditionalPositionOpeningsInformation](#jazzhr-additionalpositionopeningsinformation-object)
additionalProfileInformation | [JazzHR AdditionalProfileInformation](#jazzhr-additionalprofileinformation-object)

## Sample JSON File

A full JSON example can be downloaded [here](files/jazzhr_candidate_export.sample.json).
