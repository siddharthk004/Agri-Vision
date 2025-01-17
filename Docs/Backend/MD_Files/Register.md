# User Registration API - Siddharth Kardile
```
POST /user/register
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
``` json
{
    "username": "string",
    "email": "string",
    "password": "string",
    "address": "string",
    "contact": "string",
    "endname": "string",
    "occupation": "string",
}
```
## Response
```
200-Created

Body
{
    "message": 'User registered Successfully!',
}

```
400 - Bad Request - Invalid Registration Information

409 - Conflict

500 - Internal Server Error
