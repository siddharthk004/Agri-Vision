
# API Reference

### Start From - https://spring-bootagrivision-production.up.railway.app/api/v1/auth

#

### Register Api - Siddharth Kardile

```http
  POST /user/register
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/Register.md)

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `username` | `string` | **Required** |
| `email` | `string` | **Required** |
| `password` | `string` | **Required** |
| `address` | `string` | *Not Required*  |
| `endname` | `string` | *Not Required* |
| `contact` | `string` | *Not Required* |
| `occupation` | `string` | *Not Required* |


Takes details of user and returns the success message for user can reedirect to login page.

* Time - 1 Day
* 12 Jan 2025

#
 
### Login Api - Siddharth Kardile

```http
  POST /user/login
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/login.md)

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `username` | `string` | **Required** |
| `password` | `string` | **Required** |


Takes username and password and returns the success message And Token for user can reedirect to home page.

* Time - 1 Day
* 14 Jan 2025


#

### View Profile - Siddharth Kardile

```http
  POST /profile
```

Bearer Token

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewProfile.md)
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Token`      | `string` | **Required** |


Takes Token and returns the details of user profile.

* Time - 2 Day
* 23 Jan 2025


#

### Edit Profile - Siddharth Kardile

```http
  POST /editProfile
```

Bearer Token

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/EditProfile.md)
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `endname` | `string` | *Not Required* |
| `address` | `string` | *Not Required*  |
| `contact` | `string` | *Not Required* |
| `occupation` | `string` | *Not Required* |


Takes details or any one field and update it and returns success message.


* Time - 1 Day
* 24 Jan 2025



#

### Add Product Into Cart - Siddharth Kardile

```http
  POST /addToCart
```

Bearer Token

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/AddCartProduct.md)
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `productname` | `string` | **Required**  |
| `productcompanyname` | `string` |  **Required**   |
| `productimage` | `string` |  **Required**  |
| `afterdiscount` | `string` |  **Required**  |
| `beforediscount` | `string` |  **Required** |

Takes details of products and add it into database and returns success message.

* Time - 1 Day
* 23 Jan 2025
#

### View All Products of Cart - Siddharth Kardile

```http
  POST /viewAllCart
```

Bearer Token

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewAllCartProducts.md)


Takes token and returns details of products.

* Time - 1 Day
* 24 Jan 2025
#

### Delete Product From Cart - Siddharth Kardile

```http
  DELETE /user/deleteCart/{id}
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/DeleteCartById.md)
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id` | `int` |  **Required**  |

Takes id of products and delete it from database and returns success message.

* Time - 1 Day
* 25 Jan 2025

#

### Add Product Into WishList - Siddharth Kardile

```http
  POST /addToWishlist
```

Bearer Token

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/AddWishlistProduct.md)

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `productname` | `string` | **Required**  |
| `productcompanyname` | `string` |  **Required**   |
| `productimage` | `string` |  **Required**  |
| `afterdiscount` | `string` |  **Required**  |
| `beforediscount` | `string` |  **Required** |

Takes details of products and add it into database and returns success message.

* Time - 1 Day
* 25 Jan 2025
#

### View All Products of WishList - Siddharth Kardile

```http
  POST /viewAllWishList
```

Bearer Token

[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/ViewAllWishlistProducts.md)


Takes token and returns details of products.

* Time - 1 Day
* 24 Jan 2025

#

### Delete Product From WishList - Siddharth Kardile

```http
  DELETE /user/deleteWishList/{id}
```
[![Portfolio](https://img.shields.io/badge/Git-MdFile-%2300843e.svg?style=for-the-badge&logo=symfony&logoColor=white)](https://github.com/siddharthk004/Agri-Vision/blob/main/Docs/Backend/MD_Files/DeleteWishlistById.md)
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id` | `int` |  **Required**  |

Takes id of products and delete it from database and returns success message.

* Time - 1 Day
* 24 Jan 2025

#
