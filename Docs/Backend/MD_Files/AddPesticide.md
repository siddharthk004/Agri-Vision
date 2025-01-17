## Login API
```
POST /user/SavePesticide
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 

{
      "discount": int,
      "beforediscount": int,
      "afterdiscount": int,
      "productImage": "String",
      "productName": "String",
      "productCompanyName": "String"
 }

```
## Response
```
200 - ok
Body
{
      "id": int,
      "discount": int,
      "beforediscount": int,
      "afterdiscount": int,
      "productImage": "String",
      "productName": "String",
      "productCompanyName": "String"
  }

400 - Bad Request - Incorrect
403 - Forbidden
404 - Not Found
500 - Internal Server Error
