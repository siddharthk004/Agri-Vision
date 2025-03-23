
# Update Cart Quantity   - Siddharth Kardile

```
  POST /updateCartQuantity
```

### Request Header
```
Content-Type : application/json
```
Bearer Token <Autherization>

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `productId` | `Long` | **Required** |
| `quantity` | `int` | **Required** |

### Request Body 
```
{
        "productId": Long,
        "quantity": int

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