## Login API
```
POST /user/DeletePesticide/{id}
```

## Request Headers
```
Content-Type : application/json
```
 
## Request Body
``` json 
{
}
```
## Response
```
200 - ok
Body
{
      "success":true,
      "message": "Pesticide Deleted Successfully by Id : int"
}

400 - Bad Request 
{
      "success":false,
      "message": "Fail to Delete Pesticide Id : int"
}
403 - Forbidden
404 - Not Found
500 - Internal Server Error
