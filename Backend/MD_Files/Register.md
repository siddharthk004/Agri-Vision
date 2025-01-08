# User Registration API
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
    "name": "string",
    "email": "string",
    "password": "string",
}
```
## Response
```
200-Created
```
400 - Bad Request - Invalid Registration Information

409 - Conflict

500 - Internal Server Error
