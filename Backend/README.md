# Spring Boot Backend Features

## Features Overview
This backend supports the following functionalities:

1. **Login**
2. **Register**
3. **View Profile**
4. **Edit Profile**
5. **Add to Cart**
6. **View Cart**
7. **Add to Wishlist**
8. **View Wishlist**

---

## Endpoints and Descriptions

### 1. **Login**
- **Endpoint**: `/api/auth/login`
- **Method**: POST
- **Description**: Authenticate a user with their email and password.
- **Request Body**:
  ```json
  {
    "email": "user@example.com",
    "password": "password123"
  }
  ```
- **Response**:
  - Success: 200 OK with user details and token.
  - Error: 400 Bad Request (Invalid credentials).

### 2. **Register**
- **Endpoint**: `/api/auth/register`
- **Method**: POST
- **Description**: Create a new user account.
- **Request Body**:
  ```json
  {
    "name": "John Doe",
    "email": "user@example.com",
    "password": "password123"
  }
  ```
- **Response**:
  - Success: 201 Created with user details.
  - Error: 409 Conflict (User already exists).

### 3. **View Profile**
- **Endpoint**: `/api/user/profile`
- **Method**: GET
- **Description**: Fetch the details of the logged-in user.
- **Headers**:
  ```
  Authorization: Bearer <token>
  ```
- **Response**:
  - Success: 200 OK with user profile details.

### 4. **Edit Profile**
- **Endpoint**: `/api/user/profile`
- **Method**: PUT
- **Description**: Update the user profile details.
- **Headers**:
  ```
  Authorization: Bearer <token>
  ```
- **Request Body**:
  ```json
  {
    "name": "Updated Name",
    "email": "updated@example.com"
  }
  ```
- **Response**:
  - Success: 200 OK with updated details.

### 5. **Add to Cart**
- **Endpoint**: `/api/cart/add`
- **Method**: POST
- **Description**: Add an item to the user’s cart.
- **Headers**:
  ```
  Authorization: Bearer <token>
  ```
- **Request Body**:
  ```json
  {
    "productId": "12345",
    "quantity": 2
  }
  ```
- **Response**:
  - Success: 200 OK.

### 6. **View Cart**
- **Endpoint**: `/api/cart`
- **Method**: GET
- **Description**: View all items in the user’s cart.
- **Headers**:
  ```
  Authorization: Bearer <token>
  ```
- **Response**:
  - Success: 200 OK with cart items.

### 7. **Add to Wishlist**
- **Endpoint**: `/api/wishlist/add`
- **Method**: POST
- **Description**: Add an item to the user’s wishlist.
- **Headers**:
  ```
  Authorization: Bearer <token>
  ```
- **Request Body**:
  ```json
  {
    "productId": "12345"
  }
  ```
- **Response**:
  - Success: 200 OK.

### 8. **View Wishlist**
- **Endpoint**: `/api/wishlist`
- **Method**: GET
- **Description**: View all items in the user’s wishlist.
- **Headers**:
  ```
  Authorization: Bearer <token>
  ```
- **Response**:
  - Success: 200 OK with wishlist items.

---

## Notes:
- All secured endpoints require a valid JWT token.
- Customize the response structure and error handling as needed.

Feel free to expand this documentation based on additional features or changes.
