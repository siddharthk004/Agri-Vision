## Login API
```
GET /user/service/save
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
    "username": "String",
    "email":"String",
    "description":"String"
}
```
## Response
```
200 - ok
Body
{
    "Message":"String"
}

400 - Bad Request - Incorrect data fetching
403 - Forbidden
404 - Not Found
500 - Internal Server Error
