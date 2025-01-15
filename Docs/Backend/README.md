
# API Reference


#

#### Register Api - Siddharth Kardile

```http
  POST /user/register
```

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

#
 
#### Login Api - Siddharth Kardile

```http
  POST /user/login
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `username` | `string` | **Required** |
| `password` | `string` | **Required** |


Takes username and password and returns the success message for user can reedirect to home page.

#

#### View Profile - Siddharth Kardile

```http
  POST /user/profile
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `email`      | `string` | **Required** |


Takes email id and returns the details of user profile.

#

#### Edit Profile - Siddharth Kardile

```http
  POST /user/editprofile
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `email` | `string` | *Not Required*  |
| `endname` | `string` | *Not Required* |
| `address` | `string` | *Not Required*  |
| `contact` | `string` | *Not Required* |
| `occupation` | `string` | *Not Required* |
| `image` | `BLOB` | *Not Required* |


Takes details or any one field and update it and returns success message.


#

#### Add Product Into Cart - Siddharth Kardile

```http
  POST /user/cart
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `email` | `string` |  **Required**  |
| `productname` | `string` | **Required**  |
| `productcompanyname` | `string` |  **Required**   |
| `productimage` | `string` |  **Required**  |
| `afterdiscount` | `string` |  **Required**  |
| `beforediscount` | `string` |  **Required** |

Takes details of products and add it into database and returns success message.

#

#### View All Products of Cart - Siddharth Kardile 

```http
  POST /user/ViewAllcart
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `email` | `string` |  **Required**  |

Takes email and returns details of products.

#

#### Delete Product From Cart - Siddharth Kardile

```http
  DELETE /user/DeleteCart/{id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id` | `int` |  **Required**  |

Takes id of products and delete it from database and returns success message.


#

#### Add Product Into WishList - Siddharth Kardile

```http
  POST /user/wishlist
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `email` | `string` |  **Required**  |
| `productname` | `string` | **Required**  |
| `productcompanyname` | `string` |  **Required**   |
| `productimage` | `string` |  **Required**  |
| `afterdiscount` | `string` |  **Required**  |
| `beforediscount` | `string` |  **Required** |

Takes details of products and add it into database and returns success message.

#

#### View All Products of WishList - Siddharth Kardile

```http
  POST /user/ViewAllWishList
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `email` | `string` |  **Required**  |

Takes email and returns details of products.

#

#### Delete Product From WishList - Siddharth Kardile

```http
  DELETE /user/DeleteWishList/{id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id` | `int` |  **Required**  |

Takes id of products and delete it from database and returns success message.

#