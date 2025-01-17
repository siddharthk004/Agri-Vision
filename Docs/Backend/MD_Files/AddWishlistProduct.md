## Add Product Into WishList API - Siddharth Kardile
```
POST /user/wishlist
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
