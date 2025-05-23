# API Reference

### Start From - https://spring-bootagrivision-production.up.railway.app/api/v1/auth

# OR

### Start From - https://spring-boot-agrivision-1.onrender.com/api/v1/auth

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
| `productId` | `Long` | **Required** |

Takes details of products and add it into database and returns success message.

- Time - 1 Day
- 22 Mar 2025

#

### 6 Update Product Quantity Cart - Siddharth Kardile

```http
  POST /updateCartQuantity
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/updateCartProduct.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `productId` | `Long` | **Required** |
| `quantity` | `int` | **Required** |

Takes details of products and update product quantity from database and returns success message.

- Time - 1 Day
- 22 Mar 2025

#

### 7 View All Products of Cart - Siddharth Kardile

```http
  GET /viewAllCart
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewAllCartProducts.md)

Takes token and returns details of products.

- Time - 1 Day
- 24 Jan 2025

#

### 8 Delete Product From Cart - Siddharth Kardile

```http
  DELETE /user/deleteCart/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/DeleteCartById.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `id` | `Long` | **Required** |

Takes id of products and delete it from database and returns success message.

- Time - 1 Day
- 25 Jan 2025

#

### 9 Add Product Into WishList - Siddharth Kardile

```http
  POST /wishlist/add
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/AddWishlistProduct.md)

| Parameter            | Type     | Description  |
| :------------------- | :------- | :----------- |
| `productId`          | `Long`   | **Required** |

- Time - 1 Day
- 22 Mar 2025

#

### 10 View All Products of WishList - Siddharth Kardile

```http
  GET /wishlist/view
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewAllWishlistProducts.md)

Takes token and returns details of products.

- Time - 1 Day
- 22 Mar 2025

#

### 11 Delete Product From WishList - Siddharth Kardile

```http
  DELETE /wishlist/delete/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/DeleteWishlistById.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `id` | `Long` | **Required** |

Takes id of products and delete it from database and returns success message.

- Time - 1 Day
- 22 Mar 2025

#

### 12 Get Count of Cart - Siddharth Kardile

```http
  GET /user/cartCount
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/GetCountOfCart.md)

| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |


Takes id of products and delete it from database and returns success message.

- Time - 1 Day
- 23 Mar 2025

#

### 13 Get Count of Wishlist - Siddharth Kardile

```http
  GET /user/wishlistCount
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/GetCountOfWishlist.md)

| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |


Takes id of products and delete it from database and returns success message.

- Time - 1 Day
- 22 Mar 2025

#

#

### 1 View all product - Sakshi Ladkat

```http
 POST /user/product
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/product.md)

| Parameter            | Type     | Description  |
| :------------------- | :------- | :----------- |
| `id`                 | `int`    | **Required** |
| `discount`           | `int`    | **Required** |
| `beforediscount`     | `int`    | **Required** |
| `afterdiscount`      | `int`    | **Required** |
| `productImage`       | `string` | **Required** |
| `category`           | `string` | **Required** |
| `productCompanyName` | `string` | **Required** |

Fetch All product listed in database

- Time - 2 Day
- 12 Jan 2025

#

#

### 2 View product by id - Sakshi Ladkat

```http
 POST /user/product/id/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/productbyid.md)

| Parameter            | Type     | Description  |
| :------------------- | :------- | :----------- |
| `id`                 | `int`    | **Required** |
| `discount`           | `int`    | **Required** |
| `beforediscount`     | `int`    | **Required** |
| `afterdiscount`      | `int`    | **Required** |
| `productImage`       | `string` | **Required** |
| `category`           | `string` | **Required** |
| `productCompanyName` | `string` | **Required** |

Take id in API fetch product by id

- Time - 2 Day
- 15 Jan 2025

#

#

### 3 View product by Category - Sakshi Ladkat

```http
  POST /user/product/category/{category}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/productbycategory.md)

| Parameter            | Type     | Description  |
| :------------------- | :------- | :----------- |
| `id`                 | `int`    | **Required** |
| `discount`           | `int`    | **Required** |
| `beforediscount`     | `int`    | **Required** |
| `afterdiscount`      | `int`    | **Required** |
| `productImage`       | `string` | **Required** |
| `category`           | `string` | **Required** |
| `productCompanyName` | `string` | **Required** |

Take categoty in API fetch product by category

- Time - 1 Day
- 16 Jan 2025

#

#

### 4 Add product - Sakshi Ladkat

```http
  POST /admin/addproduct
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/addproduct.md)

| Parameter            | Type     | Description  |
| :------------------- | :------- | :----------- |
| `discount`           | `int`    | **Required** |
| `beforediscount`     | `int`    | **Required** |
| `afterdiscount`      | `int`    | **Required** |
| `productImage`       | `string` | **Required** |
| `category`           | `string` | **Required** |
| `productCompanyName` | `string` | **Required** |

Adds new Entry into the database

- Time - 2 Day
- 19 Jan 2025

#

#

### 5 Update product - Sakshi Ladkat

```http
  POST /admin/updateproduct/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/updateproduct.md)

| Parameter            | Type     | Description  |
| :------------------- | :------- | :----------- |
| `discount`           | `int`    | **Required** |
| `beforediscount`     | `int`    | **Required** |
| `afterdiscount`      | `int`    | **Required** |
| `productImage`       | `string` | **Required** |
| `category`           | `string` | **Required** |
| `productCompanyName` | `string` | **Required** |

Updates Existing Entry into the database

- Time - 2 Day
- 22 Jan 2025

#

#

#### 6 Delete product - Sakshi Ladkat

```http
  POST /admin/deleteproduct/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/Sakshi-ladkat/Docs/Backend/MD_Files/Deleteproduct.md)

| Parameter | Type  | Description  |
| :-------- | :---- | :----------- |
| `id`      | `int` | **Required** |

Delete Existing Entry into the database

- Time - 2 Day
- 26 Jan 2025

#

### 14 Edit Profile Picture - Siddharth Kardile

```http
  POST /editProfilePic
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/EditProfilePic.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `image` | `multipart` | **Required** |

- Time - 1 Day
- 27 Jan 2025

#

### 15 Otp Send Through Email - Siddharth Kardile

```http
  POST /user/forgotPassword/MailOTP
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ForgotPWDMailOTP.md)

- Time - 1 Day
- 27 Jan 2025

#

### 16 Otp Verify - Siddharth Kardile

```http
  POST /user/forgotPassword/OTP
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ForgotPWDVerifyOTP.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `otp` | `long` | **Required** |

- Time - 1 Day
- 28 Jan 2025

#

### 17 Update PassWord - Siddharth Kardile

```http
  POST /user/forgotPassword/NewPassword
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ForgotPWDNewPWD.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `password` | `String` | **Required** |

- Time - 1 Day
- 29 Jan 2025

#

### 18 Admin Query Resolve Mail Send - Siddharth Kardile

```http
  POST /admin/queryResolveMail
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/AdminQueryResolveMail.md)
| Parameter | Type | Description |
| :-------- | :------- | :-------------------------------- |
| `message` | `String` | **Required** |

- Time - 1 Day
- 30 Jan 2025

#

#

### 19 Add Comment - Siddharth Kardile

```http
  POST /user/comment
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/AddComment.md)

| Parameter | Type            | Description   |
| :-------- | :-------------- | :------------ |
| `pid`     | `Long`          | **Required**  |
| `star`    | `int`           | _No Required_ |
| `message` | `String`        | _No Required_ |
| `image`   | `MultiPartFile` | _No Required_ |
| `video`   | `MultiPartFile` | _No Required_ |

Add comment into DB also image and Video

- Time - 2 Day
- 1 Feb 2025

#

### 20 View Comment - Siddharth Kardile

```http
  POST /user/commentview/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewComment.md)

| Parameter | Type | Description |
| :-------- | :--- | :---------- |

- Time - 1 Day
- 2 Feb 2025

#

### 21 Admin View service - Siddharth Kardile

```http
  GET /admin/ViewHelpCenterList
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewHelpCenterList.md)

| Parameter | Type | Description |
| :-------- | :--- | :---------- |

get all service message in a list

- Time - 1 Day
- 3 Feb 2025

#

### 22 User Search - Siddharth Kardile

```http
  GET /user/search/{query}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/Search.md)

| Parameter | Type | Description |
| :-------- | :--- | :---------- |

Call any Quesry Related to product name It will fetch that all products

- Time - 2 Day
- 6 Feb 2025

#

### 23 User Help Center - Siddharth Kardile

```http
  POST /user/serviceMsgSend
```

Bearer Token <Autherization>

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/serviceMsgSend.md)

| Parameter | Type   | Description  |
| :-------- | :----- | :----------- |
| Message   | String | **Required** |

- Time - 2 Day
- 8 Feb 2025

#

### 24 Admin Service Mail Sending Reply - Siddharth Kardile

```http
  POST /admin/serviceMailSend
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/serviceMailSend.md)

| Parameter | Type   | Description  |
| :-------- | :----- | :----------- |
| mail      | String | **Required** |
| message   | String | **Required** |

- Time - 4 Day
- 12 Feb 2025

#

### 25 Admin View All Add - Siddharth Kardile

```http
  GET /admin/add
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/serviceMailSend.md)

| Parameter | Type   | Description  |
| :-------- | :----- | :----------- |

- Time - 1 Day
- 23 Mar 2025

#

### 26 Admin View Add By Id - Siddharth Kardile

```http
  GET /admin/add/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/serviceMailSend.md)

| Parameter | Type   | Description  |
| :-------- | :----- | :----------- |
| id   | `Long` | **Required** |

- Time - 1 Day
- 24 Mar 2025

#

### 27 Admin Delete Add By Id - Siddharth Kardile

```http
  POST /admin/Deleteadd/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/serviceMailSend.md)

| Parameter | Type   | Description  |
| :-------- | :----- | :----------- |
| id   | `Long` | **Required** |

- Time - 1 Day
- 24 Mar 2025

#

### 28 Admin Update Add By Id - Siddharth Kardile

```http
  POST /admin/Updateadd/{id}
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/serviceMailSend.md)

| Parameter | Type   | Description  |
| :-------- | :----- | :----------- |
| id   | `Long` | **Required** |
| image   | `Multipart` | **Required** |

- Time - 1 Day 
- 24 Mar 2025

#

### 29 Admin Add new Advertisement - Siddharth Kardile

```http
  POST /admin/addImage
```

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/serviceMailSend.md)

| Parameter | Type   | Description  |
| :-------- | :----- | :----------- |
| image   | `Multipart` | **Required** |

- Time - 1 Day
- 24 Mar 2025

#
