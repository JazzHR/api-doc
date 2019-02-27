## Field Types

<aside class="notice">
Note: All field types can be set to <strong>null</strong>
</aside>

<aside class="notice">
Note: All field types are surrounded by double quotes except for <strong>number</strong> & <strong>boolean</strong> (see examples).
</aside>

<aside class="notice">
Note: Date and datetime values are assumed to be in Coordinated Universal Time (UTC). Datetimes are ISO-8601 formatted.
</aside>

Types | Description | Example
----- | ----------- | -------
string | Arbitrary string of characters/digits/etc. | **"Foo bar 123!"**
number | Integers & floats (no commas or letters) | **50000** or **3.14**
boolean | true or false | **true** or **false**
date | YYYY-MM-DD | **"1982-09-30"**
datetime | YYYY-MM-DD HH:mm:ss | **“1982-09-30 14:15:16”**
template | HTML Template string | **"&lt;p>Job Description&lt;/p>"**
