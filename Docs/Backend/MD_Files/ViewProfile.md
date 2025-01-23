## Profile API - Siddharth  Kardile
```
POST /profile
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

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
  "username" : "String",
  "image" : "BLOB",
  "email" : "String",
  "endname" : "String",
  "address" : "String",
  "contact" : "String",
  "occupation" : "String",
}

400 - Bad Request - User Not Found
401 - unauthorized 
404 - Not Found
500 - Internal Server Error
