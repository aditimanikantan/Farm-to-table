# Farm-to-Table E-commerce Website

Developer:
- Full Stack: ADITI MANIKANTAN

## Project Overview

The "Farm-to-Table" project is a modern e-commerce platform connecting farmers directly with consumers. This platform emphasizes a seamless farm-to-table experience, enabling direct transactions and building a sustainable marketplace. Users can browse fresh agricultural products, manage orders, and support local farming communities.

## Table of Contents

- [Project Features](#project-features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage Guidelines](#usage-guidelines)

## Project Features

### User Types and Accounts

- **Customers (Registered Users)**:
  - Register using email (no verification required).
  - Can make purchases from the shop.
  
- **Administrator/Merchant**:
  - Manages the entire product catalog.
  - Oversees e-commerce operations including user accounts, product listings, order fulfillment, and sales analytics.

### Functional Specifications

#### General

- **Registration and Authentication**:
  - Users register with an email and username.
  - Login/Logout functionality with route protection for admin-exclusive areas.

#### E-commerce Management (Administrator/Merchant Users)

- **Dashboard**:
  - Manage user accounts and view registered users.
  - Product listings with details such as name, type (crops or poultry), price, description, and quantity.
  - Order fulfillment and confirmation.
  - Sales reports showing products sold and sales income, with summaries for weekly, monthly, and annual transactions.

#### Shop (Customer Users)

- **Product Listings and Order Fulfillment**:
  - Browse products, manage shopping cart, and confirm orders.
  - Cart management including item deletion, item count, and total price calculation.
  - Orders can be canceled if not confirmed by the merchant.

## Technology Stack

- **Front End**: React JS
- **Back End**: Node JS with Express JS
- **Database**: MongoDB

# Installation

# 1. Clone the repository:
``` bash
git clone <repository-url>
cd <repository-directory>
```

# 2. Install dependencies:
``` bash
npm install
```

# 2. Start the development server and the node server:
``` bash
npm start
cd ./server/
node ./server.js/
```

# Usage Guidelines

1. Registration:
    - Customers can register using their email and a username.
2. Login:
    - Users must log in to access the platform's features.
3. Shopping:
    - Customers can browse products, add items to their shopping cart, and place orders.
4. Admin Dashboard:
    - Administrators can manage products, user accounts, and view comprehensive sales reports and analytics.
