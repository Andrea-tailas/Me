# E-Commerce Platform

This project is a comprehensive e-commerce platform designed to provide a seamless shopping experience for customers and a robust management system for administrators.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

### User Features
- **User Registration and Authentication**: Secure user registration and login.
- **Product Browsing**: Browse and search for products across various categories.
- **Product Details**: View detailed information about each product, including images, descriptions, and reviews.
- **Shopping Cart**: Add products to the shopping cart and manage quantities.
- **Checkout**: Secure checkout process with payment gateway integration.
- **Order History**: View past orders and order status.

### Admin Features
- **Product Management**: Add, update, and delete products.
- **Order Management**: View and manage customer orders.
- **User Management**: Manage registered users and their roles.
- **Analytics Dashboard**: View sales analytics and generate reports.

## Technology Stack

### Frontend
- **React**: JavaScript library for building user interfaces.
- **Redux**: State management for React applications.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Axios**: Promise-based HTTP client for making API requests.

### Backend
- **Node.js**: JavaScript runtime for building scalable network applications.
- **Hono**: Web framework for building fast web applications in Node.js.
- **Drizzle ORM**: Type-safe SQL ORM for PostgreSQL.
- **PostgreSQL**: Relational database for storing product, user, and order data.

### Other Tools
- **Git**: Version control system.
- **Postman**: API testing and development tool.
- **Docker**: Containerization platform for consistent environments.

## Installation

### Prerequisites
- Node.js and `pnpm` installed
- PostgreSQL installed and running
- Docker (optional for containerization)

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/e-commerce-platform.git
    cd e-commerce-platform
    ```

2. **Install dependencies**:
    ```bash
    pnpm install
    cd client
    pnpm install
    cd ..
    ```

3. **Set up environment variables**:
    - Create a `.env` file in the root directory and add the following variables:
      ```env
      DATABASE_URL=your_postgresql_connection_string
      JWT_SECRET=your_jwt_secret
      ```

4. **Run database migrations**:
    ```bash
    pnpm run migrate
    ```

5. **Run the development server**:
    ```bash
    pnpm run dev
    ```

6. **Run the frontend**:
    ```bash
    cd client
    pnpm start
    ```

## Usage

1. **Open your browser** and navigate to `http://localhost:3000` to access the frontend.
2. **Use Postman** or another API client to interact with the backend API at `http://localhost:5000/api`.

### Admin Access

To access the admin panel, you need to manually set a user's role to `admin` in the PostgreSQL database. Use pgAdmin or another PostgreSQL client to update the user role.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or issues, please contact [tituswaititu96@gmail.com].
