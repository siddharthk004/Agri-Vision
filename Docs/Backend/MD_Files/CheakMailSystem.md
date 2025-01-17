## Profile API
```
POST /user/mail
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
    "email" : "String"
}
```
## Response
```
200 - Success
Body
{
  "message" : "String"
}

400 - Bad Request - An Error Occurred
403 - Forbidden
404 - Not Found
500 - Internal Server Error
