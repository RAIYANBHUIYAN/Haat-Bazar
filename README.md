# Haat-Bazar

Haat-Bazar is a full-stack e-commerce marketplace platform that connects buyers and sellers, facilitating online transactions with administrative oversight.

## Project Structure

The project is split into two main components:

- **Frontend**: React.js application with Tailwind CSS
- **Backend**: Node.js REST API with MongoDB

## Features

- **User Management**
  - Buyer accounts
  - Seller accounts
  - Admin dashboard

- **Product Management**
  - Product listings
  - Product search and filtering
  - Product reviews

- **Order Processing**
  - Shopping cart
  - Order placement
  - Transaction history

- **Communications**
  - Buyer and seller complaints system
  - Review system

## Technology Stack

### Frontend
- React.js
- Tailwind CSS
- Bootstrap components

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

## Getting Started

### Prerequisites
- Node.js (v14+)
- MongoDB
- npm or yarn

### Setup and Installation

#### Backend
1. Navigate to the backend directory:
   ```
   cd hatbazar-backend-main
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   - Create or modify `.env` file with appropriate database connection strings and secrets

4. Start the server:
   ```
   npm start
   ```

#### Frontend
1. Navigate to the frontend directory:
   ```
   cd Haat-Bazar-main/frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

4. Open your browser and go to `http://localhost:3000`

## Project Architecture

### Frontend Structure
- **components/**: UI components organized by user roles (Buyer, Seller, Admin)
- **images/**: Static image assets
- **src/**: Core application code

### Backend Structure
- **routes/**: API endpoints definition
- **controllers/**: Business logic for each route
- **models/**: MongoDB data models
- **middleware/**: Authentication and request processing

## API Documentation

The API provides endpoints for:
- User authentication and management
- Product CRUD operations
- Order processing
- Reviews and complaints

## Contributors

[Add contributor names here]

## License

This project is licensed under the MIT License - see the LICENSE file for details. 