## Add Product Into WishList API - Siddharth Kardile
```
POST /user/wishlist/add
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

```
 
## Request Body
``` json 
{
  "productId" : "Long"
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
