## Add Product Into Cart API - Siddharth Kardile
```
POST /user/addToCart
```

## Request Headers
```
Content-Type : application/json
bearer <token>  
```
 
## Request Body
``` json 
{
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

400 - Bad Request - user Not Found
401 - Unauthorized
404 - Not Found
500 - Internal Server Error
