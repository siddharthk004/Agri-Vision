## Admin Query Resolve Mail Send API - Siddharth Kardile
```
POST /admin/queryResolveMail
```

## Request Headers
```
Bearer <Token>

```
 
## Request body
```  
{
  "message" : "String"
}
```
## Response
```
200 - Success
Body
{
  "message" : "String"
}

400 - Bad Request - message
401 - Unauthorized
404 - Not Found
500 - Internal Server Error
