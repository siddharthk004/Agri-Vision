## Edit Profile API - Siddharth Kardile
```
POST /editProfile
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

```
 
## Request Body
``` json 
{
  "endname" : "String",
  "address" : "String",
  "contact" : "String",
  "occupation" : "String"
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
401 - Unauthorized
404 - Not Found
500 - Internal Server Error
