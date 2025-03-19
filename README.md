E-Commerce Cart System (React.js & Node.js)

This is a Mini E-Commerce Cart System built using React.js for the frontend and Node.js + Express for the backend. It allows users to view products, add them to the cart, update quantities, proceed to checkout, and receive an order confirmation.

Features : 

View products fetched from an API

Add products to the cart and manage quantities

Remove items and view a dynamic total price

Checkout with a validated form (Formik & Yup)

Order confirmation page

Navigation between Home, Cart, and Checkout pages (React Router)

API integration with a backend server



Steps to Set Up and Run the Project

1. Install Dependencies
   Navigate to the backend folder and run: `npm install`
    Navigate to the frontend folder and run: `npm install`

2. Start the Backend Server
   In the backend folder, run: `node server.js`

3. Start the Frontend Application
   In the frontend folder, run: `npm start`

4. Access the Application
   Open your browser and go to: `http://localhost:3000`


Project Structure ShopEase/ │── backend/ # Node.js & Express backend │ ├── server.js # API routes for products & checkout │ ├── package.json # Backend dependencies │── frontend/ # React.js frontend │ ├── src/ │ │ ├── components/ │ │ │ ├── ProductList.js │ │ │ ├── Cart.js │ │ │ ├── Checkout.js │ │ │ ├── OrderConfirmation.js │ │ ├── App.js │ │ ├── index.js │ ├── package.json # Frontend dependencies │── README.md # Documentation
