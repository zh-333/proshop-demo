# ProShop eCommerce Platform - Zi Hao

This project is an eCommerce platform built using the MERN stack and Redux Toolkit. It features a full shopping cart system, including PayPal and credit/debit card payment options. This is version 2.0, which integrates Redux Toolkit. The platform provides a complete online shopping experience for users, as well as a range of admin features for managing products, users, and orders.

## Features

- Fully functional shopping cart
- Product reviews and rating system
- Top products displayed in a carousel
- Product pagination
- Search functionality for products
- User profiles with order history
- Admin tools for product, user, and order management
- Option to mark orders as delivered
- Checkout process with options for shipping and payment methods
- Integration with PayPal and credit/debit card payments
- Database seeder for adding sample products and users

## Usage

To get started with the platform, you'll need to create a MongoDB database and obtain a PayPal client ID. After that, you can set up your environment and run the application.

### Environment Variables

Rename the `.env.example` file to `.env` and add the following variables:

`NODE_ENV=development`
`PORT=5000`
`MONGO_URL=ADD_YOUR_MONGO_URI`
`JWT_SECRET=ADD_YOUR_SECRET`
`PAYPAL_CLIENT_ID=ADD_YOUR_PAYPAL_CLIENT_ID`
`PAYPAL_APP_SECRET=ADD_YOUR_PAYPAL_APP_SECRET`
`PAYPAL_API_URL=ADD_YOUR_PAYPAL_API_URL`
`PAGINATION_LIMIT = 8`

You can change the `JWT_SECRET` and `PAGINATION_LIMIT` to suit your preferences.

### Installation

To install the necessary dependencies for both the frontend and backend:

`npm install cd frontend npm install`

### Running the Application

To run the application in development mode, execute the following command:

`npm run dev`

This will start both the frontend on port 3000 and the backend on port 5000. If you want to run only the backend, use:

`npm run server`

## Build & Deploy

To create a production build for the frontend:

`cd frontend npm run build`

### Seeding the Database

You can seed the database with sample users and products, or clear all data using the following commands:

#### 1. Import data

`npm run data`

#### 2. Destroy data

`npm run data`