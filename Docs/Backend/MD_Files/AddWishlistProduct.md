## Add Product Into WishList API - Siddharth Kardile
```
POST /user/addToWishlist
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

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
401 - unAuthorized
404 - Not Found
500 - Internal Server Error
