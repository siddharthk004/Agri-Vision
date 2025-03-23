## View All WishList Products API - Siddharh Kardile
```
POST /wishlist/view
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

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
  "productname" : "String",
  "productcompanyname" : "String",
  "productimage" : "String",
  "afterdiscount" : "String",
  "befoerdiscount" : "String",
  "discount" : "String",
}

400 - Bad Request - user Not Found
401 - unauthorized
404 - Not Found
500 - Internal Server Error
