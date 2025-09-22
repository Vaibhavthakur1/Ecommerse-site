# **Darshan Enterprises E-Commerce Site**

This is a full-stack e-commerce website built with the MERN stack (MongoDB, Express.js, React, Node.js). It provides a complete online shopping experience with features for both customers and administrators.

## **🚀 Features**

### **Customer-Facing Features:**

* **User Authentication:** Secure user registration and login system using JWT (JSON Web Tokens).  
* **Product Browsing:** View a list of all products or browse by categories like Electronics, Fashion, Home Appliances, Gaming, and Books.  
* **Product Search:** Find products quickly with the search bar in the navigation.  
* **Product Details:** View detailed information about each product, including descriptions, ratings, and related products.  
* **Shopping Cart:** Add products to a side-cart, view the total price, and remove items.  
* **Checkout:** Place orders with a simple checkout process.  
* **Dark/Light Mode:** Toggle between dark and light themes for a comfortable viewing experience.

### **Admin Features:**

* **Admin Dashboard:** A dedicated dashboard for administrators to manage the site.  
* **Order Management:** View all customer orders and update their status (e.g., "Shipped," "Delivered").

## **🛠️ Technologies Used**

### **Frontend:**

* **React:** A JavaScript library for building user interfaces.  
* **React Router:** For declarative routing in the React application.  
* **React Toastify:** For displaying toast notifications.  
* **Sass:** A CSS preprocessor for writing more maintainable styles.

### **Backend:**

* **Node.js:** A JavaScript runtime for building the server-side application.  
* **Express.js:** A web application framework for Node.js, used for building the RESTful APIs.  
* **MongoDB:** A NoSQL database for storing user and order information.  
* **Mongoose:** An Object Data Modeling (ODM) library for MongoDB and Node.js.  
* **JWT (JSON Web Token):** For securing the API endpoints and authenticating users.  
* **CORS:** Middleware for enabling Cross-Origin Resource Sharing.

## **⚙️ Setup and Installation**

### **Prerequisites**

* Node.js and npm (or yarn) installed on your machine.  
* A MongoDB database instance (local or cloud-based).

### **Backend Setup**

1. **Navigate to the server directory:**  
   Bash  
   cd server

2. **Install dependencies:**  
   Bash  
   npm install

3. **Create a .env file in the server directory and add the following environment variables:**  
   MONGO\_URI=\<your\_mongodb\_connection\_string\>  
   JWT\_SECRET\_KEY=\<your\_jwt\_secret\_key\>  
   PORT=8080

4. **Start the backend server:**  
   Bash  
   npm start

   The server will be running on the port specified in your .env file (e.g., http://localhost:8080).

### **Frontend Setup**

1. **Navigate to the client directory:**  
   Bash  
   cd client

2. **Install dependencies:**  
   Bash  
   npm install

3. **Start the frontend development server:**  
   Bash  
   npm start

   The application will open in your browser at http://localhost:3000.

