# -totalitycorp-frontend-challenge
Complete MERN Stack Ecommerce App project 

## About

An eCommerce web application built using the MERN stack for selling and buying various products.
The MERN Stack eCommerce App is a full-featured web application that allows users to browse, search for, and purchase a wide range of products. Registered users can also sell their own products through the platform. This project serves as a comprehensive example of building an eCommerce site using the MERN stack.

## Demo

You can check out the live demo of the app here(https://dull-moccasins.cyclic.cloud).


## Features

- User registration and authentication
- Product browsing and searching
- Shopping cart functionality
- Checkout and payment processing (via Braintree)
- Order history and tracking
- Product reviews and ratings
- Seller profiles and product management
- Admin dashboard for managing products and orders
- Responsive design for mobile and desktop

## Technologies Used

- **MongoDB**: Database for storing product, user, and order data.
- **Express.js**: Backend framework for handling API requests.
- **React**: Frontend library for building user interfaces.
- **Node.js**: Runtime environment for the backend.
- **Braintree**: Payment processing for secure transactions.
- **Bootstrap**: CSS framework for responsive design.
- **Deployment**: cyclic is used(similar software: Heroku, Netlify)
- **Other libraries**: Axios, React Router, Bcrypt, JWT, etc.



## Installation and Getting Started

To get this project up and running, follow these steps:

### Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js**: Make sure you have Node.js installed on your machine. You can download it from [nodejs.org](https://nodejs.org/).

- **MongoDB**: Ensure you have MongoDB installed and running. You can download and install it from [mongodb.com](https://www.mongodb.com/).

### Clone the Repository
--git clone https://github.com/vidyasagar14-bit/-totalitycorp-frontend.git

#### Navigate to the Project Folder
   cd  project-name

#### Install backend dependencies
    npm install

#### Navigate to the client directory
    cd client

#### Install frontend dependencies
    npm install

 ### Configure Environment Variables
  Create a .env file in the project root and add the following environment variables:

   plaintext
  -PORT=3000

  -MONGODB_URI=your-mongodb-uri

  -SECRET_KEY=your-secret-key

  -Replace your-mongodb-uri with your MongoDB connection URI and your-secret-key with your preferred secret key for JWT authentication.

### Start the Development Server
#### Return to the project root
     cd ..

#### Start both the backend and frontend
     npm run dev
