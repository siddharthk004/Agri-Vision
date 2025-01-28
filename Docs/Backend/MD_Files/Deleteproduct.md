
#
# Delete product  - Sakshi Ladkat 

```
  POST /admin/deleteproduct/{id}
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
       
}
```
200-ok

### Response
```
{
    
}

```
400 - Bad Request 

404 - Not Found

500 - Internal Server Error

#