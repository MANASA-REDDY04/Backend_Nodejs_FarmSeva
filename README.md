# Food E-Commerce Backend Multivendor Dashboard

## Overview

This project is the backend for a multivendor dashboard for a food e-commerce platform. It allows multiple vendors to manage their products, orders, and other business operations through a centralized dashboard.
The platform is designed to handle various functionalities such as product management, vendor management, and more.

## Features

- **Vendor Management**: Allows vendors to register, manage their profiles, and list their products.
- **Product Management**: Vendors can add, edit, or remove products from their catalog.
- **Authentication & Authorization**: Secure login for admins and vendors with role-based access control.

## Technology Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Encryption**: bcrypt

## Setup and Installation

### Prerequisites

- Node.js (v14 or above)
- MongoDB (local or cloud instance)

### Installation Steps

1. **Clone the Repository**
    ```bash
    git clone https://github.com/MANASA-REDDY04/Backend_Nodejs_FarmSeva.git
    cd Backend_Nodejs_FarmSeva
    ```

2. **Install Dependencies**
    ```bash
    npm install
    ```

3. **Environment Variables**
    - Create a `.env` file in the root directory and add the following environment variables:

    ```plaintext
    PORT=4000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the Server**
    ```bash
    npm start
    ```

5. **Access the API**
    - The server will start on `http://localhost:4000`. You can access the API at `http://localhost:4000/vendor/all-vendors`.

### API Documentation

- The API documentation can be found [here](https://drive.google.com/file/d/1YPZeqCqXK6uQjm9yKKS5HJfyyGJ6-TCA/view?usp=sharing).
- You can test the endpoints using Postman or any API testing tool.

## Testing

- Run unit and integration tests using:
    ```bash
    npm test
    ```

## Acknowledgments

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
