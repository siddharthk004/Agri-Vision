## Admin View All Help Center Request API - Siddharh Kardile
```
GET /admin/ViewHelpCenterList

```

## Request Headers
```
Content-Type : application/json

```

## Request Header
``` 
{
}

```
## Response
```
200 - Success
Body
{
  "id" : "Long",
  "name" : "String",
  "mail" : "String",
  "message" : "String"
}

400 - Bad Request
401 - unauthorized
404 - Not Found
500 - Internal Server Error
