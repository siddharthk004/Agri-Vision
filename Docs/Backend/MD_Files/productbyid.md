View Product By category API - Sakshi Ladkat 
POST /product/id/{id}

Request Header
Content-Type : application/json

Request Body 
{

}

200-ok

Response
{
        "id": int,
        "discount": int,
        "beforediscount": int,
        "afterdiscount": int,
        "productImage": String,
        "productName": String,
        "category": "String,
        "productCompanyName": String

}

400 - Bad Request 
404 - Not Found
500 - Internal Server Error
