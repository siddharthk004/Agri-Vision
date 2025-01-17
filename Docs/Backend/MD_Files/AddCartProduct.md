## Add Product Into Cart API - Siddharth Kardile
```
POST /user/cart
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
  "email" : "String",
  "productname" : "String",
  "productcompanyname" : "String",
  "productimage" : "String",
  "afterdiscount" : "String",
  "befoerdiscount" : "String",
  "discount" : "String",
}
```
## Response
```
200 - Success
Body
{
  "message" : "String"
}

400 - Bad Request - Email Not Found
404 - Not Found
500 - Internal Server Error
