# Title 1
## Title 2
### Title 3

``` json
{
  "id": 4000123,
  "user": "user@example.com",
  "location": "https://api.example.com/v1/people/4000123"
}
```

> Curl Example:

``` bash
curl -v "https://super.user%40stoney-cloud.org:secret@api.example.com/v1/people"
```
> JSON Example

``` json
{
  "error": {
    "module": "core",
    "code": 422,
    "message": "The request was well-formed but was unable to be followed due to semantic errors."
    "details" : [
      {
        "module": "core",
        "code" : 1006,
        "field" : "isCompany",
        "message" : "is invalid, true or false will be accepted"
      },
      {
        "module": "core",
        "code" : 5123,
        "field" : "password",
        "message" : "Password cannot be blank"
      }
    ]
  }
}
```

2<sup>31</sup>-1 to -2<sup>31</sup>
