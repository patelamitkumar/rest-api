# rest-api

## Commonly used verbs
- GET - Query for a resource
- POST - Create a resource OR if you combine with the resource name /search the endpoint becomes search
- PUT - Create or Replace
- DELETE - Delete a resource

Not so common but handy to use 
- PATCH - Partial update

## Resource Namings
- Always use nouns except for count.
- Singular vs plural - Better to use plural

## Error Codes
The list of codes in internet is exhaustive but I am putting together the most common ones for used for most of the use cases.
- 200 Success
- 201 Created
- 204 No content
- 400 Bad request
- 401 Unauthorized
- 403 Forbidden
- 404 Not Found
- 409 Duplicate
- 500 Internal Server Error
- 502
- 503

## Error Schemas

{
"code": "<A custom code>",
"info": "<The message to be presented to consumer>",
"description": "<More details about the error>",
"errors": [<list of errors here>]
}
