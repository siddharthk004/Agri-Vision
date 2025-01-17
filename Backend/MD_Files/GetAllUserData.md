## Login API
```
POST /user/service/save
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
}
```
## Response
```
200 - Success
Body
{
  "id" : "int",
  "username" : "String",
  "endname" : "String",
  "email" : "String",
  "address" : "String",
  "contact" : "String",
}

400 - Bad Request - Incorrect username
403 - Forbidden
404 - Not Found
500 - Internal Server Error
