## Profile API
```
GET /user/cart/{email}
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
  "email" : "String",
}
```
## Response
```
200 - Success
Body
{
  "count" : int,
}

400 - Bad Request - Email Not Found
403 - Forbidden
404 - Not Found
500 - Internal Server Error
