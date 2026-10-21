# OnlineShop — E-Commerce Web Application

## Project Overview

OnlineShop is an e-commerce web application developed using C#, ASP.NET Core MVC, Entity Framework Core, and SQL Server. The application provides an online shopping experience for customers and an administration area for managing products, categories, brands, orders, discounts, and customer reviews.

The project focuses on implementing practical e-commerce workflows, organizing application responsibilities, and managing relational data through Entity Framework Core.

## Target Users

- **Customers:** Browse products, search and filter the catalog, manage shopping carts and favorites, place orders, make online payments, and manage their accounts.
- **Administrators:** Manage products, categories, brands, discounts, orders, product colors, and customer reviews through the administration area.

## Technical Stack

- **Programming Language:** C#
- **Framework:** ASP.NET Core MVC
- **ORM:** Entity Framework Core
- **Database:** Microsoft SQL Server
- **Authentication:** ASP.NET Core Identity
- **Payment Integration:** Stripe Checkout
- **Data Transfer:** Data Transfer Objects (DTOs)
- **Frontend:** Razor Views, HTML, CSS, JavaScript
- **Database Configuration:** Fluent API, LINQ, entity relationships, and query filters

## Architecture & Design

The application separates responsibilities across domain, application, infrastructure, and presentation-related parts of the solution.

Key design and implementation details include:

- **Entity Framework Core:** Manages database access, entity relationships, and database mappings.
- **ASP.NET Core Identity:** Supports user registration, authentication, and account management.
- **Separation of Concerns:** Organizes application functionality across different parts of the solution.
- **Soft Deletion:** Supports marking selected records as removed instead of immediately deleting them.
- **Global Query Filters:** Applies filtering rules to selected entities.
- **Audit Timestamps:** Manages entity creation and update timestamps.
- **Database Indexes:** Defines indexes on selected product, category, and brand fields.
- **Relationship Configuration:** Defines relationships between products, categories, brands, carts, orders, payments, discounts, and reviews.

### Database Entities

The database context includes entities for:

- Products, product images, attributes, and colors
- Categories and brands
- Users and delivery addresses
- Shopping carts and cart items
- Orders, order items, and payments
- Discounts and product discounts
- Favorites and product comments

## Product Catalog & Management

The product catalog supports browsing and discovering products, while the administration area provides tools for managing catalog information.

Key features include:

- Product listing and detailed product pages
- Category- and brand-based product browsing
- Product search by keyword, category, and price range
- Sorting and pagination
- Product images, attributes, and color options
- Related products and product ratings
- Product discount management
- Administrative product creation, editing, and removal
- Category, brand, and category-image management

## Shopping Cart & Order Management

The shopping and ordering workflows allow customers to select products, manage quantities, and proceed through the checkout process.

Key features include:

- Adding and removing cart items
- Updating product quantities
- Managing the shopping cart before checkout
- Creating orders from cart items
- Integrating Stripe Checkout into the online payment workflow
- Viewing paid and unpaid orders
- Viewing order details and payment status
- Administrative order review and management

## Customer Accounts & Engagement

The application includes customer account features and tools for interacting with products.

Key features include:

- User registration and login
- SMS- and email-based OTP verification flows
- Profile updates and password changes
- Delivery address management
- Personal favorites lists
- Product reviews and ratings
- Review submissions with comments, strengths, and weaknesses
- Administrative review moderation

## Key Features

- E-commerce catalog and product discovery
- Shopping cart and order workflows
- Stripe Checkout integration
- Customer account and address management
- Favorites and product reviews
- Administrative catalog and order management
- Discount management
- Role-based authorization and authorization policies
- Entity Framework Core relationships and Fluent API configuration
- Soft deletion, query filters, and audit timestamps
- SQL Server relational database integration

## My Role

Designed and developed the application's main e-commerce workflows and supporting backend functionality, including:

- Implementing MVC controllers for products, accounts, carts, orders, and administration.
- Developing product search, filtering, sorting, and pagination.
- Configuring Entity Framework Core mappings, relationships, indexes, and query filters.
- Integrating ASP.NET Core Identity for user authentication and account management.
- Implementing favorites, product reviews, discounts, and order workflows.
- Integrating Stripe Checkout into the payment process.
- Developing administrative features for managing catalog data, orders, and customer reviews.

## Project Showcase

The following screenshots demonstrate selected customer-facing features and administrative functionality.

### Homepage

![OnlineShop Homepage](docs/images/homepage.png)

### Categories & Products

![Categories and Products](docs/images/categories-products.png)

### Product Details

![Product Details](docs/images/product-details.png)

### Shopping Cart

![Shopping Cart](docs/images/shopping-cart.png)

### Checkout & Payment

![Checkout and Payment](docs/images/checkout-payment.png)

### Customer Profile

![Customer Profile](docs/images/customer-profile.png)

### Admin Product Management

![Admin Product Management](docs/images/admin-products.png)

### Architecture Overview

![OnlineShop Architecture](docs/images/architecture-overview.png)

## Contact

For professional inquiries and collaboration, feel free to connect with me on LinkedIn.
