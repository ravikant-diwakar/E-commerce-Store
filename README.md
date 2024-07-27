# E-Commerce Store

An advanced E-commerce store built using the MERN stack, offering customizable product views, product listings, search functionality, cart management, checkout process, and payment gateway integration. This project ensures seamless navigation and a smooth user experience.

## Features

- **Customizable Product Views**: Toggle between list and grid views for product display.
- **Product Listings**: Comprehensive product listings with sorting and filtering options.
- **Search Functionality**: Efficient search bar to quickly find products.
- **Cart Management**: Add, update, and remove items in the cart.
- **Checkout Process**: Streamlined checkout process with order summary.
- **Payment Gateway Integration**: Secure payment processing using [Payment Gateway] (e.g., Stripe, PayPal).
- **Responsive Design**: Optimized for desktop and mobile devices.

## Tech Stack

- **Frontend**:
  - React.js
  - Redux
  - CSS

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB

- **Payment Gateway**:
  - [Payment Gateway]

## Installation

### Prerequisites

- Node.js
- MongoDB
- NPM/Yarn

### Clone the Repository

```bash
git clone https://github.com/ravikant-diwakar/ecommerce-store.git
cd ecommerce-store
```

### Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

### Environment Variables

Create a `.env` file in the backend directory and add the following:

```
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYMENT_GATEWAY_KEY=your_payment_gateway_key
```

### Run the Application

#### Backend

```bash
cd backend
npm start
```

#### Frontend

```bash
cd frontend
npm start
```

## Usage

- Visit `http://localhost:3000` to access the frontend.
- Use `http://localhost:5000/api` for backend API endpoints.

## API Endpoints

### Products

- `GET /api/products`: Get all products
- `GET /api/products/:id`: Get a single product by ID

### Cart

- `POST /api/cart`: Add item to cart
- `GET /api/cart`: Get all items in cart
- `DELETE /api/cart/:id`: Remove item from cart

### Orders

- `POST /api/orders`: Create a new order
- `GET /api/orders/:id`: Get order details by ID

### Users

- `POST /api/users/register`: Register a new user
- `POST /api/users/login`: Authenticate user and get token

### Payments

- `POST /api/payments`: Process payment

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/FeatureName`)
3. Commit your Changes (`git commit -m 'Add some FeatureName'`)
4. Push to the Branch (`git push origin feature/FeatureName`)
5. Open a Pull Request

---
