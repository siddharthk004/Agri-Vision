## Edit Profile Picture API - Siddharth Kardile
```
POST /editProfilePic
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

```
 
## Request part
```  
{
  "image" : "MultiPartFile"
}
```
## Response
```
200 - Success
Body
{
  "message" : "String"
}

400 - Bad Request - NO image Found
401 - Unauthorized
404 - Not Found
500 - Internal Server Error
