# Philosopher's Store 🛒

Philosopher's Store is a comprehensive full-stack e-commerce application built with the MERN stack, offering a seamless shopping experience with secure payments through the Braintree API, robust user authentication, and a role-based access control for admins and customers alike.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=18Cqvrz9KXoSrXfPJB8Hv6NCYksfRFfO_" width="49%">
  <img src="https://drive.google.com/uc?export=view&id=1OGFilRoh3ybFXaADMKBt8zEt4I31PK7R" width="49%">
  <img src="https://drive.google.com/uc?export=view&id=100xSxK4SsvxctcvT7790KFwsev7uVxEM" width="49%">
  <img src="https://drive.google.com/uc?export=view&id=1z1oyqvt7exvgbdFZZ39yqXdBKqKNf5Pz" width="49%">
</p>

---

## ✨ Features

-   **Product Listings**: Browse and search through a wide range of available products.
-   **Cart Management**: Easily add, update, and remove items from the shopping cart with a seamless checkout flow.
-   **Order Tracking**: An integrated system allows users to track the status of their placed orders.
-   **Secure Payments**: Integrated with **Braintree API** for safe, reliable, and PCI-compliant payment processing.
-   **Authentication & Authorization**: Secure user login and signup functionality using **Bcrypt** for hashing passwords and **JSON Web Tokens (JWT)** for session management.
-   **Role-Based Access Control (RBAC)**:
    -   **Admin Dashboard**: Admins can manage products (create, update, delete), view orders, and manage users.
    -   **User Dashboard**: Customers have personalized access to their order history and profile information.

---

## 🛠️ Tech Stack

This project is built using modern web technologies to deliver a fast, responsive, and secure user experience.

-   **Frontend**: ReactJS, TailwindCSS
-   **Backend**: NodeJS, ExpressJS
-   **Database**: MongoDB
-   **Payments**: Braintree API
-   **Authentication**: Bcrypt, JWT (JSON Web Tokens)

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

-   Node.js (v14 or later)
-   npm or yarn
-   MongoDB (local instance or a cloud service like MongoDB Atlas)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/philosophers-store.git](https://github.com/your-username/philosophers-store.git)
    cd philosophers-store
    ```

2.  **Install server dependencies:**
    ```sh
    cd server
    npm install
    ```

3.  **Install client dependencies:**
    ```sh
    cd ../client
    npm install
    ```

4.  **Set up Environment Variables:**
    Create a `.env` file in the `server` directory and add the following variables. You will need to get your own credentials from MongoDB and Braintree.

    ```env
    # Server Configuration
    PORT=8000

    # MongoDB Connection
    MONGO_URI=your_mongodb_connection_string

    # JWT Configuration
    JWT_SECRET=your_super_secret_jwt_key

    # Braintree API Credentials
    BRAINTREE_MERCHANT_ID=your_braintree_merchant_id
    BRAINTREE_PUBLIC_KEY=your_braintree_public_key
    BRAINTREE_PRIVATE_KEY=your_braintree_private_key
    ```

5.  **Run the application:**
    -   To start the backend server (from the `server` directory):
        ```sh
        npm start
        ```
    -   To start the frontend development server (from the `client` directory):
        ```sh
        npm start
        ```

The application should now be running! Open your browser and navigate to `http://localhost:3000`.
