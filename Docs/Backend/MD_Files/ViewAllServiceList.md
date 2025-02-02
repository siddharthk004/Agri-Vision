# View All Service List API - Siddharth Kardile 
```
GET /admin/ViewHelpCenterList
```

### Request Header
```
Content-Type : application
```

### Request Body 
```
{

}
```
200-ok

### Response
```
{
        "id": int,
        "username": String,
        "email": String,
        "discription": String
}
```
400 - Bad Request 

404 - Not Found

500 - Internal Server Error
