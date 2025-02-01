## View All Comment Of that Product API - Siddharh Kardile
```
POST /user/commentview/{id}
```

## Request Headers
```
Content-Type : application/json

```

## Request Header
``` 
{
  "id" : "int"
}

```
## Response
```
200 - Success
Body
{
  "pid" : "Long",
  "Uname" : "String",
  "star" : "int",
  "message" : "String",
  "image" : "MultiPartFile",
  "video" : "MultiPartFile",
}

400 - Bad Request
401 - unauthorized
404 - Not Found
500 - Internal Server Error
