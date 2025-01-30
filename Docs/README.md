# API Reference

### Start From - https://spring-bootagrivision-production.up.railway.app/api/v1/auth

#

### 1 Register Api - Siddharth Kardile

```http
  POST /user/register
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/Register.md)

| Parameter    | Type     | Description    |
| :----------- | :------- | :------------- |
| `username`   | `string` | **Required**   |
| `email`      | `string` | **Required**   |
| `password`   | `string` | **Required**   |
| `address`    | `string` | _Not Required_ |
| `endname`    | `string` | _Not Required_ |
| `contact`    | `string` | _Not Required_ |
| `occupation` | `string` | _Not Required_ |

Takes details of user and returns the success message for user can reedirect to login page.

- Time - 1 Day
- 12 Jan 2025

# Wire Frame By Atharva Khaladkar

<img width="350" src="https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/FrontEnd/Wireframe/Sign-up.png">
#

### 2 Login Api - Siddharth Kardile

```http
  POST /user/login
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/login.md)

| Parameter  | Type     | Description  |
| :--------- | :------- | :----------- |
| `username` | `string` | **Required** |
| `password` | `string` | **Required** |

Takes username and password and returns the success message And Token for user can reedirect to home page.

- Time - 1 Day
- 14 Jan 2025

#

### 3 View Profile - Siddharth Kardile

```http
  POST /profile
```
Bearer Token <Autherization>


[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewProfile.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `Token` | `string` | **Required** |

Takes Token and returns the details of user profile.

- Time - 2 Day
- 23 Jan 2025

#

### 4 Edit Profile - Siddharth Kardile

```http
  POST /editProfile
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/EditProfile.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `endname` | `string` | _Not Required_ |
| `address` | `string` | _Not Required_ |
| `contact` | `string` | _Not Required_ |
| `occupation` | `string` | _Not Required_ |

Takes details or any one field and update it and returns success message.

- Time - 1 Day
- 24 Jan 2025

#

### 5 Add Product Into Cart - Siddharth Kardile

```http
  POST /addToCart
```
Bearer Token <Autherization>


[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/AddCartProduct.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `productname` | `string` | **Required** |
| `productcompanyname` | `string` | **Required** |
| `productimage` | `string` | **Required** |
| `afterdiscount` | `string` | **Required** |
| `beforediscount` | `string` | **Required** |

Takes details of products and add it into database and returns success message.

- Time - 1 Day
- 23 Jan 2025

#

### 6 View All Products of Cart - Siddharth Kardile

```http
  POST /viewAllCart
```
Bearer Token <Autherization>


[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewAllCartProducts.md)

Takes token and returns details of products.

- Time - 1 Day
- 24 Jan 2025

#

### 7 Delete Product From Cart - Siddharth Kardile

```http
  DELETE /user/deleteCart/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/DeleteCartById.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `id` | `int` | **Required** |

Takes id of products and delete it from database and returns success message.

- Time - 1 Day
- 25 Jan 2025

#

### 8 Add Product Into WishList - Siddharth Kardile

```http
  POST /addToWishlist
```
Bearer Token <Autherization>


[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/AddWishlistProduct.md)

| Parameter            | Type     | Description  |
| :------------------- | :------- | :----------- |
| `productname`        | `string` | **Required** |
| `productcompanyname` | `string` | **Required** |
| `productimage`       | `string` | **Required** |
| `afterdiscount`      | `string` | **Required** |
| `beforediscount`     | `string` | **Required** |

Takes details of products and add it into database and returns success message.

- Time - 1 Day
- 25 Jan 2025

#

### 9 View All Products of WishList - Siddharth Kardile

```http
  POST /viewAllWishList
```
Bearer Token <Autherization>


[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewAllWishlistProducts.md)

Takes token and returns details of products.

- Time - 1 Day
- 24 Jan 2025

#

### 10 Delete Product From WishList - Siddharth Kardile

```http
  DELETE /user/deleteWishList/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/DeleteWishlistById.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `id` | `int` | **Required** |

Takes id of products and delete it from database and returns success message.

- Time - 1 Day
- 24 Jan 2025

#

#
### 11 View all product - Sakshi Ladkat 

```http
 POST /user/product
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/product.md)

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `int` | **Required** |
|`discount`|`int`|**Required**|
|`beforediscount`|`int`|**Required**|
|`afterdiscount`|`int`|**Required**|
|`productImage`|`string`|**Required**|
|`category`|`string`|**Required**|
|`productCompanyName`|`string`|**Required**|

Fetch All product listed in database
* Time - 2 Day
* 12 Jan 2025
#

#
### 12 View product by id  - Sakshi Ladkat

```http
 POST /user/product/id/{id}
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/productbyid.md)

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `int` | **Required** |
|`discount`|`int`|**Required**|
|`beforediscount`|`int`|**Required**|
|`afterdiscount`|`int`|**Required**|
|`productImage`|`string`|**Required**|
|`category`|`string`|**Required**|
|`productCompanyName`|`string`|**Required**|

Take id in API fetch product by id
* Time - 2 Day
* 15 Jan 2025
#

#
### 13 View product by Category  - Sakshi Ladkat 

```http
  POST /user/product/category/{category}
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/productbycategory.md)

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `int` | **Required** |
|`discount`|`int`|**Required**|
|`beforediscount`|`int`|**Required**|
|`afterdiscount`|`int`|**Required**|
|`productImage`|`string`|**Required**|
|`category`|`string`|**Required**|
|`productCompanyName`|`string`|**Required**|

Take categoty in API fetch product by category
* Time - 1 Day
* 16 Jan 2025
#

#
### 14 Add product  - Sakshi Ladkat 

```http
  POST /admin/addproduct
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/addproduct.md)



| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|`discount`|`int`|**Required**|
|`beforediscount`|`int`|**Required**|
|`afterdiscount`|`int`|**Required**|
|`productImage`|`string`|**Required**|
|`category`|`string`|**Required**|
|`productCompanyName`|`string`|**Required**|

Adds new Entry into the database 
* Time - 2 Day
* 19 Jan 2025
#

#
### 15 Update product  - Sakshi Ladkat 

```http
  POST /admin/updateproduct/{id}
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/updateproduct.md)



| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|`discount`|`int`|**Required**|
|`beforediscount`|`int`|**Required**|
|`afterdiscount`|`int`|**Required**|
|`productImage`|`string`|**Required**|
|`category`|`string`|**Required**|
|`productCompanyName`|`string`|**Required**|

Updates Existing Entry into the database 
* Time - 2 Day
* 22 Jan 2025
#

#
#### 16 Delete product  - Sakshi Ladkat 

```http
  POST /admin/deleteproduct/{id}
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/Deleteproduct.md)



| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|`id`|`int`|**Required**|

Delete Existing Entry into the database 
* Time - 2 Day
* 26 Jan 2025
#

### 17 Edit Profile Picture - Siddharth Kardile

```http
  POST /editProfilePic
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/EditProfilePic.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `image` | `multipart` |   **Required** |


- Time - 1 Day
- 27 Jan 2025

#
### 18 Otp Send Through Email - Siddharth Kardile

```http
  POST /user/forgotPassword/MailOTP
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ForgotPWDMailOTP.md)


- Time - 1 Day
- 27 Jan 2025

#
### 19 Otp Verify - Siddharth Kardile

```http
  POST /user/forgotPassword/OTP
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ForgotPWDVerifyOTP.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `otp` | `long` |   **Required** |

- Time - 1 Day
- 28 Jan 2025

#

### 20 Update PassWord - Siddharth Kardile

```http
  POST /user/forgotPassword/NewPassword
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ForgotPWDNewPWD.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `password` | `String` |   **Required** |

- Time - 1 Day
- 29 Jan 2025

#

### 21 Admin Query Resolve Mail Send - Siddharth Kardile

```http
  POST /admin/queryResolveMail
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/AdminQueryResolveMail.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `message` | `String` |   **Required** |

- Time - 1 Day
- 30 Jan 2025

#
