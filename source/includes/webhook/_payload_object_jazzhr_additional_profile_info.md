## JazzHR AdditionalProfileInformation Object

> Sample JazzHR AdditionalProfileInformation JSON Object

```json
{
    "number": {
        "rating": "number",
        "workflowStatus": "string",
        "workflowStatusCategory": "string",
        "workflowDispositionDatetime": "datetime"
    }
}

```
### Notable Attributes

Attribute | Type | Description | Possible Answers
---------| ---- | -----
number.workflowStatusCategory | string | Category of step in the related workflow | "Active", "Hired", "Not Hired"