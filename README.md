# Amazon 🛒

This project is an Amazon clone developed using React, Node.js, and MongoDB. It replicates the basic functionality of an e-commerce website, including user authentication, product browsing, shopping cart, and order processing.

## Features ✨


- **User Authentication**: Sign up, login, and logout functionality with secure password hashing.
- **Product Management**: Browse products, view product details, and search for products.
- **Shopping Cart**: Add, remove, and update product quantities in the cart.
- **Order Processing**: Place orders and view order history.
- **Payment Integration**Integrate with payment gateways for order payments.
- **Responsive Design:**:Optimized for various screen sizes and devices.

## Some Images 🎥

![GitHub - devraj17112000_E-commerceapp - Google Chrome 21-06-2024 01_48_00](https://github.com/devrajpardhi04/Amazon-Clone/assets/133412139/8cde88c3-8b1f-45ba-8e86-032ff3d24952)
![GitHub - devraj17112000_E-commerceapp - Google Chrome 21-06-2024 01_48_05](https://github.com/devrajpardhi04/Amazon-Clone/assets/133412139/73e2a4b8-3090-4f93-8136-8883d61080fc)
![GitHub - devraj17112000_E-commerceapp - Google Chrome 21-06-2024 01_48_09](https://github.com/devrajpardhi04/Amazon-Clone/assets/133412139/c2dc2b60-84a8-4162-9490-49242fd3cf0a)
![GitHub - devraj17112000_E-commerceapp - Google Chrome 21-06-2024 01_48_20](https://github.com/devrajpardhi04/Amazon-Clone/assets/133412139/d49c7502-a621-40b3-9628-db84320afb8f)
![GitHub - devraj17112000_E-commerceapp - Google Chrome 21-06-2024 01_47_46](https://github.com/devrajpardhi04/Amazon-Clone/assets/133412139/4e6b4817-da66-466b-a9ec-64799693f7f9)

## Tech Stack

- **Frontend**:React, Redux, CSS, Material-UI.
- **Backend**: Node.js, Express
- **Database**:MongoDB
- **Authentication**:JWT (JSON Web Tokens)
- **Payment Gateway**Stripe API

## Getting Started 🚀

Follow these instructions to set up the project locally.

### Installation

1. Clone the repository
   `git clone https://github.com/your-username/amazon-clone.git`

2. Navigate to the project directory
   `cd amazon-clone`

3. Install dependencies:
   ```bash
   npm install
   cd client
   npm install

   ```

4. Create a `.env` file in the server directory and add your MongoDB URI and Stripe API keys
   ```
   MONGO_URI=your_mongo_uri
   STRIPE_SECRET_KEY=your_stripe_secret_key
   JWT_SECRET=your_jwt_secret
   ```

5. Start the development servers
   ```
   npm run dev
   ```


## Usage 💻

- **Browse Products**: View a variety of products on the homepage.
- **Product Details**: Click on a product to see detailed information.
- **Add to Cart**: Add items to your shopping cart and proceed to checkout.
- **Secure Payment**: Complete purchases using the integrated Stripe payment gateway.
- **User Authentication**: Sign up or log in to manage your orders and account information.

## Built With 🛠️

- **React** - JavaScript library for building user interfaces
- **Node.js** - JavaScript runtime for server-side development
- **Express.js** - Web framework for Node.js
- **MongoDB** - NoSQL database for scalable data storage
- **Material-UI** - React component library for styling
- **styled-components** - Library for component-level styling
- **Redux** - State management library
- **Stripe** - Payment processing platform
- **JWT** - JSON Web Tokens for authentication


## Folder Structure 📂

```
amazon-clone/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.js
│   │   │   ├── Product.js
│   │   │   └── ...
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── ProductDetail.js
│   │   │   ├── Cart.js
│   │   │   └── ...
│   │   ├── redux/
│   │   │   ├── store.js
│   │   │   ├── userSlice.js
│   │   │   ├── productSlice.js
│   │   │   └── ...
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
├── server/
│   ├── controllers/
│   │   ├── userController.js
│   │   ├── productController.js
│   │   └── ...
│   ├── models/
│   │   ├── User.js
│   │   ├── Product.js
│   │   └── ...
│   ├── routes/
│   │   ├── userRoutes.js
│   │   ├── productRoutes.js
│   │   └── ...
│   ├── middlewares/
│   │   ├── authMiddleware.js
│   │   └── ...
│   ├── server.js
│   └── ...
├── .env
├── package.json
├── package-lock.json
└── README.md
└── ...
```
   
