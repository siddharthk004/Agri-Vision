## Profile API
```
POST /user/profile
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
  "username" : "String",
  "image" : "BLOB"
  "email" : "String",
  "endname" : "String",
  "address" : "String",
  "contact" : "String",
  "occupation" : "String",
}

400 - Bad Request - User Not Found
403 - Forbidden
404 - Not Found
500 - Internal Server Error
