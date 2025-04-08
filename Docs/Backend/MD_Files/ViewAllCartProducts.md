## View All Cart Products API - Siddharh Kardile
```
GET /viewAllCart
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

```
 
## Request Body
``` json 
{}

```
## Response
```
200 - Success
Body
{
  "product" : {
                "productname" : "String",
                "productcompanyname" : "String",
                "productimage" : "String",
                "afterdiscount" : "String",
                "befoerdiscount" : "String",
                "discount" : "String",
              },
  "quantity" : "int",
  "id" : "int"
  }

400 - Bad Request - user Not Found
401 - unauthorized
404 - Not Found
500 - Internal Server Error
