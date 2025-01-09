## Login API
```
POST /user/DeleteFertilizer/{id}
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
      "message": "Fertilizer Deleted Successfully by Id : int"
}

400 - Bad Request 
{
      "success":false,
      "message": "Fail to Delete Fertilizer Id : int"
}
403 - Forbidden
404 - Not Found
500 - Internal Server Error
