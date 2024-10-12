# Spy-Buy-Backend

This repository contains the backend code for the Spy-Buy e-commerce platform.

Frontend for this project : https://github.com/Shivang-X/Spy-Buy-Frontend

## Features

- User authentication and authorization using JWT
- Product management (create, update, delete)
- Secure payments with Stripe integration
- Cloud image storage with Cloudinary
- Email notifications via SMTP

## Technology Stack

- **Node.js**
- **Express.js**
- **MongoDB**
- **Stripe**
- **Cloudinary**

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Shivang-X/Spy-Buy-Backend.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Spy-Buy-Backend
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Create a `.env` file and add the following:

    ```bash
    PORT=4000
    DB_URI=<Your MongoDB URI>
    JWT_SECRET=<Your JWT Secret>
    CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
    CLOUDINARY_API_KEY=<Your Cloudinary API Key>
    CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
    STRIPE_SECRET_KEY=<Your Stripe Secret Key>
    SMTP_HOST=<SMTP Host>
    SMTP_PORT=<SMTP Port>
    SMTP_EMAIL=<Your SMTP Email>
    SMTP_PASSWORD=<Your SMTP Password>
    ```

## Running the Application

To start the server in development mode:

```bash
npm run dev
```
The server will run at http://localhost:4000.

## API Documentation

- **Authentication:** Register, login, and token management
- **Products:** Create, read, update, and delete products
- **Payments:** Secure payments via Stripe
- **Image Upload:** Cloudinary for product images
  
## Contributing
Feel free to fork the repository and submit pull requests.
