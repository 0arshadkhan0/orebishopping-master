# E-Commerce Website
This project is a full-stack eCommerce platform built using the MERN stack (MongoDB, Express, React, Node.js), along with Redux for state management, Tailwind CSS for responsive design, and Sass for custom styling. The platform enables users to browse products, add them to the cart, and make purchases securely.

Features
User Authentication: Secure user registration and login using JWT.
Product Management: Users can browse a variety of products with dynamic categories and filters.
Cart & Checkout: Add products to the cart, modify quantities, and proceed to secure checkout with integrated payment options.
Order Management: Users can view their order history and track their order status.
Admin Dashboard: Admin can manage products, categories, orders, and users.
Responsive Design: The site is fully responsive, adapting to different screen sizes using Tailwind CSS.
Optimized Performance: The website is optimized for fast loading and SEO-friendly.
Dark Mode: Toggle between light and dark themes for user preference.
Technologies Used
Frontend:

React: Single-page application framework.
Redux: For global state management of cart, user, and product data.
Tailwind CSS: For styling and creating a responsive UI.
Sass: Used for advanced styling and CSS modularity.
Backend:

Node.js & Express: For building a scalable, RESTful API.
MongoDB: NoSQL database for storing product and user information.
JWT: For secure authentication and authorization.
Other Tools:

Axios: For handling API requests.
Stripe/PayPal Integration: For secure payment processing.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/username/ecommerce-mern-redux.git
cd ecommerce-mern-redux
Install dependencies for both frontend and backend:

bash
Copy code
npm install
cd client
npm install
Create a .env file for environment variables:

Backend:
MONGO_URI: MongoDB connection string
JWT_SECRET: JWT secret key
PAYMENT_GATEWAY_API_KEY: Payment gateway API key (Stripe/PayPal)
Frontend:
You can configure any necessary environment variables like API endpoints here.
Run the development servers:

For the backend:

bash
Copy code
npm run server
For the frontend:

bash
Copy code
cd client
npm start
Usage
Register or log in as a user to access features like adding products to the cart and checking out.
Admin users can log in to the dashboard to manage products, orders, and users.
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you would like to contribute to this project.

This README gives a clear overview of the eCommerce platform's features and how to get started with the project. You can modify any details to fit your specific implementation.



### Here are some screenshots of the project
 
![1](https://github.com/user-attachments/assets/fc3410d3-8c80-41a1-b480-f363c6cdb7d6)
![2](https://github.com/user-attachments/assets/261334af-ea87-45b5-8682-d85e9225b178)
![3](https://github.com/user-attachments/assets/c8b9135e-56eb-4738-9fd4-6dd1010c7d26)
