
#
# Add product  - Sakshi Ladkat 

```
  POST /admin/addproduct
```
### Request Header
```
Content-Type : application/json
```


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|`discount`|`int`|**Required**|
|`beforediscount`|`int`|**Required**|
|`afterdiscount`|`int`|**Required**|
|`productImage`|`string`|**Required**|
|`category`|`string`|**Required**|
|`productCompanyName`|`string`|**Required**|


### Request Body 
```
{
        "discount": int,
        "beforediscount": int,
        "afterdiscount": int,
        "productImage": String,
        "productName": String,
        "category": "String,
        "productCompanyName": String

}
```
201-Created

### Response
```
{

}

```
400 - Bad Request 

404 - Not Found

500 - Internal Server Error


#
