## Login API
```
POST /user/save
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
    "username": "String",
    "email": "String",
    "description": "String"
}
```
## Response
```
200 - Success
Body
{
}

400 - Bad Request - Incorrect username
403 - Forbidden
404 - Not Found
500 - Internal Server Error
