## Forgot Password Update New PAssword API - Siddharth Kardile
```
POST /user/forgotPassword/NewPassword
```

## Request Headers
```
Bearer <Token>

```
 
## Request body
```  
{
  "password" : "String"
}
```
## Response
```
200 - Success
Body
{
  true
}

400 - Bad Request - false
401 - Unauthorized
404 - Not Found
500 - Internal Server Error
