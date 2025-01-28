## Forgot Password Verify API - Siddharth Kardile

```
POST /user/forgotPassword/OTP
```

## Request Headers
```
Bearer <Token>

```
 
## Request part
```  
{
  "userotp" : "Long"
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
