# Full Stack Food Delivery App

Welcome to the Full Stack Food Delivery App! This project is a comprehensive food delivery platform built using the MERN stack (MongoDB, Express.js, React, Node.js) with integrated Stripe payment processing.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Features
- **User Authentication:** Sign up, log in, and log out.
- **Browse Restaurants:** View a list of restaurants and their menus.
- **Cart Management:** Add or remove items from the cart.
- **Order Placement:** Place orders and view order history.
- **Stripe Integration:** Secure payment processing with Stripe.
- **Admin Panel:** Manage restaurants, menus, and orders.



## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites
- Node.js
- npm (Node Package Manager) or yarn
- MongoDB (Local or Atlas)
- Stripe Account (for payment processing)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fullstack-food-delivery-app.git
   cd fullstack-food-delivery-app
2. Backend
   ```bash
    cd backend
    npm install
3. Frontend
    ```bash
     cd frontend
     npm install
4. Admin
   ```bash
   cd admin
   npm install
5. Start MongoDB Server
6. Start the Backend Server
   ```bash
   cd backend
   npm run server
7. Start the Frontend Server
   ```bash
   cd frontend
   npm run dev
8. Start the Frontend Server
     ```bash
   cd admin
   npm run dev

### Configuration
**Backend**
 - Create a .env file in the backend directory and add the following:
```bash
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```
- Go to backend->config->db.js and paste your_mongo_db_connection_string.

## Technologies Used

- **Frontend:**
  - React.js
  - Redux for state management
  - Axios for HTTP requests

- **Backend:**
  - Node.js with Express.js
  - MongoDB (NoSQL database)
  - Mongoose (MongoDB ODM)
  - JWT for user authentication
  - Stripe API for payment processing

- **Other:**
  - RESTful APIs for communication between frontend and backend
  - MongoDB Atlas (optional) for remote database hosting
  - Git for version control

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

Make sure to update tests as appropriate.




