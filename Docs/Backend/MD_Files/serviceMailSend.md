# Admin Service Mail Sending to User - Siddharth Kardile 
```
POST /admin/serviceMailSend
```

### Request Header
```
Content-Type : application
```

### Request Body 
```
{
        "mail" : "String",
        "message": "String"
}
```
200-ok

### Response
```

200 - success
{
}
```
400 - Bad Request 

404 - Not Found

500 - Internal Server Error
