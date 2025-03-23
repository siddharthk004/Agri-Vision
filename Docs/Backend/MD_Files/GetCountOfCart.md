## Get Count Of Cart API - Siddharh Kardile
```
GET /user/cartCount
```

## Request Headers
```
Content-Type : application/json

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
  "count": int
}

400 - Bad Request - user Not Found
401 - unauthorized
404 - Not Found
500 - Internal Server Error
