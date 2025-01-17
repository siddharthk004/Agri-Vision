## View All Cart Products API - Siddharh Kardile
```
POST /user/ViewAllcart
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
  "productname" : "String",
  "productcompanyname" : "String",
  "productimage" : "String",
  "afterdiscount" : "String",
  "befoerdiscount" : "String",
  "discount" : "String",
}

400 - Bad Request - Email Not Found
404 - Not Found
500 - Internal Server Error
