# User Login API  - Siddharth Kardile
```
POST /user/login
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
``` json
{
    "username": "string",
    "password": "string"
}
```
## Response
```
200-Created

Body
{
    "success": true,
    "message": "Login successful"
}

```
400 - Bad Request - Invalid User Details

409 - Conflict

500 - Internal Server Error
