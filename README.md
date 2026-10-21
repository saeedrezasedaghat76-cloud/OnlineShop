# OnlineShop — E-Commerce Web Application

## Overview

OnlineShop is an e-commerce web application built with ASP.NET Core MVC, C#, Entity Framework Core, and SQL Server. It provides customers with product browsing, shopping cart management, order placement, online checkout, and account management features, along with an administration area for managing products, categories, brands, discounts, orders, and customer reviews.

The project focuses on implementing practical e-commerce workflows, organizing application logic, and managing relational data using Entity Framework Core.

## Features

### Customer Features

- **Product Catalog:** Browse products by category and brand, view product details, images, attributes, colors, and related products.
- **Search and Filtering:** Search products by keyword, category, and price range, with sorting and pagination.
- **Shopping Cart:** Add or remove items and update product quantities before checkout.
- **Favorites:** Save products to a personal favorites list.
- **Order Management:** Place orders and view order history, payment status, and order details.
- **Online Payments:** Integrate Stripe Checkout into the payment workflow.
- **Customer Accounts:** Register, sign in, update profile information, change passwords, and manage delivery addresses.
- **Verification Flows:** Support OTP-based verification through SMS and email.
- **Product Reviews:** Submit ratings, comments, strengths, and weaknesses for products.

### Administration Features

- **Product Management:** Create, update, and remove products, including product images and attributes.
- **Category and Brand Management:** Manage product categories, category images, and brands.
- **Order Management:** Review orders and inspect order details.
- **Discount Management:** Create discounts and associate them with products.
- **Review Moderation:** Search, review, approve, and unapprove customer comments.
- **Product Color Management:** Add and manage product color options.
- **Access Control:** Restrict administrative operations using role-based authorization and authorization policies.

## Technology Stack

| Category | Technologies |
|---|---|
| Language | C# |
| Framework | ASP.NET Core MVC |
| ORM | Entity Framework Core |
| Database | Microsoft SQL Server |
| Authentication | ASP.NET Core Identity |
| Payments | Stripe Checkout |
| Data Transfer | Data Transfer Objects (DTOs) |
| Frontend | Razor Views, HTML, CSS, JavaScript |
| Data Access | LINQ, EF Core relationships, Fluent API |
| Dependency Management | Built-in ASP.NET Core Dependency Injection |

## Architecture and Database Design

The application organizes its code across domain, application, infrastructure, and presentation-related namespaces, separating responsibilities across different parts of the system.

Key implementation details include:

- **Entity Framework Core:** Configures entity relationships and database mappings using Fluent API.
- **ASP.NET Core Identity:** Supports user authentication and account management.
- **Soft Deletion:** Uses removal flags and timestamps for selected entities instead of immediately deleting records.
- **Global Query Filters:** Applies filtering rules to selected entities, including products, categories, brands, orders, and payments.
- **Audit Timestamps:** Handles creation and update timestamps through the database context.
- **Database Indexes:** Defines indexes on selected product, category, and brand fields.
- **Relational Data Modeling:** Manages relationships between products, categories, brands, carts, orders, payments, discounts, and customer reviews.

### Architecture Overview

![OnlineShop Architecture](docs/images/architecture-overview.png)

## Application Screenshots

The following screenshots demonstrate selected customer-facing and administrative features of the application.

### Homepage

![OnlineShop Homepage](docs/images/homepage.png)

### Categories and Products

![Categories and Products](docs/images/categories-products.png)

### Product Details

![Product Details](docs/images/product-details.png)

### Shopping Cart

![Shopping Cart](docs/images/shopping-cart.png)

### Checkout and Payment

![Checkout and Payment](docs/images/checkout-payment.png)

### Customer Profile

![Customer Profile](docs/images/customer-profile.png)

### Admin Product Management

![Admin Product Management](docs/images/admin-products.png)

## My Role and Contributions

As the developer of this project, I worked on implementing the main e-commerce workflows and their supporting backend functionality, including:

- Developing MVC controllers and application workflows for products, carts, orders, accounts, and administration.
- Implementing product search, filtering, sorting, and pagination.
- Configuring Entity Framework Core mappings, relationships, query filters, and database indexes.
- Integrating ASP.NET Core Identity for authentication and account management.
- Implementing product favorites, customer reviews, discount management, and order workflows.
- Integrating Stripe Checkout into the online payment process.
- Building administrative features for managing catalog data, orders, and customer reviews.

## Potential Improvements

Areas for future development include:

- Adding automated unit and integration tests.
- Improving application configuration and secrets management.
- Expanding structured logging and error handling.
- Reviewing database query performance and indexing as usage grows.
- Strengthening payment lifecycle handling and webhook-based verification.
- Adding a REST API for clients that require API-based access.

## Repository Notes

This repository is intended to showcase the application's functionality, technical stack, architecture, and selected user interface screens.

The screenshots provide a visual overview of the project without requiring visitors to browse the complete application source code.

## Contact

For professional inquiries and collaboration, feel free to connect with me on LinkedIn.
