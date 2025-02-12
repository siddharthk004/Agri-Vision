# User Search Query API - Siddharth Kardile 
```
GET /user/search/{query}
```

### Request Header
```
Content-Type : application
```

### Request Body 
```
{

}
```
200-ok

### Response
```
{
        "id": int,
        "discount": int,
        "beforediscount": int,
        "afterdiscount": int,
        "productImage": String,
        "productName": String,
        "category": String,
        "productCompanyName": String
}
```
400 - Bad Request 

404 - Not Found

500 - Internal Server Error
