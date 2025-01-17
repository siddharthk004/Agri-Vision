## Profile API
```
POST /user/editprofile
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
  "email" : "String",
  "endname" : "String",
  "address" : "String",
  "contact" : "String",
  "occupation" : "String",
  "image" : "BLOB"
}
```
## Response
```
200 - Success
Body
{
  "message" : "String"
}

400 - Bad Request - User Not Found
403 - Forbidden
404 - Not Found
500 - Internal Server Error
