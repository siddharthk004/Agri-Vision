## Delete WishList Products API - Siddharth Kardile
```
DELETE /user/deleteWishList/{id}
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
    "id" : int
}
```
## Response
```
200 - ok
Body
{
      "success":true,
      "message": "Wishlist Deleted Successfully by Id : int"
}

400 - Bad Request 
{
      "success":false,
      "message": "Fail to Delete Wishlist Id : int"
}
404 - Not Found
500 - Internal Server Error
