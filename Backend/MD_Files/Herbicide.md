## Login API
```
GET /user/ViewAllHerbicide
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
200 - ok
Body
{
    {
        "id": int,
        "discount": int,
        "beforediscount": int,
        "afterdiscount": int,
        "productImage": "String",
        "productName": "String",
        "productCompanyName": "String"
    },
    {
        "id": int,
        "discount": int,
        "beforediscount": int,
        "afterdiscount": int,
        "productImage": "String",
        "productName": "String",
        "productCompanyName": "String"
    },
    .......
}

400 - Bad Request - Incorrect data fetching
403 - Forbidden
404 - Not Found
500 - Internal Server Error
