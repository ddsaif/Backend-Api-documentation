## 1. Generate Token Api

```curl
https://jhthkkgf-3000.inc1.devtunnels.ms/user/generateToken
Post method
```
### Request Body
```json

{
    "clientID": "",
    "secretKey": ""

}
```
### Response Body (Status: 200)
```json
{

    "status": true,

    "message": "Token generated successfully",

    "data": {

        "token": "eyJhbGciOiJIUzUxMiIsInR5cCI6IkpXVCJ9.eyJ0aW1lIjoiTW9uIEFwciAyOCAyMDI1IDE2OjI2OjA5IEdNVCswNTMwIChJbmRpYSBTdGFuZGFyZCBUaW1lKSIsImlhdCI6MTc0NTgzNzc2OSwiZXhwIjoxNzQ1ODQwNzY5fQ.C-9NZzCNjH5GNI3MDH6byVGRKmCgTdzSTG9GUziIXGMkRkC2QIYSPiGKo1ZRUgtK2fIoIjhexLi5eKgo53PVzQ"

    }

}
```
## 2. Register Api
```curl
https://jhthkkgf-3000.inc1.devtunnels.ms/user/web-register
Post Method
```

### Request Body
```json

{

  "reg_username": "John Doe",
  "reg_email": "saif.rahman+rest@example.com",
  "dob": "1995-08-15",
  "reg_user_city": "New York",
  "reg_mobile": "1234567890",
  "reg_create_app_account": true,
  "reg_usr_ip_address": "192.168.1.1",
  "reg_password": "SecurePassword123",
  "country": "USA",
  "region": "New York",
  "city": "New York City",
  "zip": "10001"
}
```

### Response Body (Status: 201)
```json

{
    "status": true,
    "message": "Web User has been successfully registered."
}
```
