## Add comment API - Siddharth Kardile
```
POST /user/comment
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

```
 
## Request Body
``` json 
{
  "pid" : "Long",
  "star" : "int",
  "message" : "String",
  "image" : "MultiPartFile",
  "video" : "MultiPartFile",
}
```
## Response
```
200 - Success
Body
{
  "message" : "String"
}

400 - Bad Request - user Not Found
401 - unAuthorized
404 - Not Found
416 - Video Size Limit exceeded
500 - Internal Server Error
