## Forgot Password Send Mail With OTP API - Siddharth Kardile

```
POST /user/forgotPassword/MailOTP
```

## Request Headers
```
Bearer <Token>

```
 
## Request part
```  
{
}
```
## Response
```
200 - Success
Body
{
  "message" : "String"
}

400 - Bad Request 
401 - Unauthorized
404 - Not Found
500 - Internal Server Error
