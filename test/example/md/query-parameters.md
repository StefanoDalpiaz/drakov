FORMAT: 1A

# Specification with query parameters
See [Blueprint API - URI parameters section](https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md#12-uri-parameters-section)


## Things [/api/query]

### Get without query parameter [GET]

+ Response 200 (application/json;charset=UTF-8)

    + Body

           {
              "id": "raw"
            }


## Things [/api/query{?param1}]

+ Parameters
    + param1 (string, `12345`) ... Parameter for the request

### Get with query parameter [GET]

+ Response 200 (application/json;charset=UTF-8)

    + Body

            {
               "id": "parameter1"
            }


## Things [/api/query{?param2}]

+ Parameters
    + param2 (string, `12345`) ... Parameter for the request

### Get with query parameter [GET]

+ Response 200 (application/json;charset=UTF-8)

    + Body

            {
               "id": "parameter2"
            }



## Things [/api/query?param1{&param2}]

+ Parameters
    + param1 (string, `12345`) ... Parameter for the request
    + param2 (string, `12345`) ... Parameter for the request

### Get with query parameter [GET]

+ Response 200 (application/json;charset=UTF-8)

    + Body

            {
               "id": "parameter1_parameter2"
            }


## Things [/api/query{?param2,param3}]

+ Parameters
    + param1 (string, `12345`) ... Parameter for the request
    + param2 (string, `12345`) ... Parameter for the request

### Get with query parameter [GET]

+ Response 200 (application/json;charset=UTF-8)

    + Body

            {
               "id": "parameter2_parameter3"
            }
