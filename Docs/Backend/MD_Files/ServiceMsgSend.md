## User Service Message Send API - Siddharh Kardile
```
POST /user/serviceMsgSend
```

## Request Headers
```
Content-Type : application/json
Bearer <Token>

```
 
## Request Body
``` json 
{
  "message": string
}

```
## Response
```
200 - Success
Body
{
}

400 - Bad Request - user Not Found
401 - unauthorized
404 - Not Found
500 - Internal Server Error
