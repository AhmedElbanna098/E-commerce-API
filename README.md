# E-Commerce API

## Introduction

Welcome to the E-Commerce API! This platform serves as a robust backend solution for handling products, carts, orders, and user authentication within an e-commerce system. Offering a wide array of endpoints, it facilitates tasks such as product browsing, cart management, order placement, and order history retrieval. Moreover, it supports CRUD operations for product management, including image uploads.

## Technology Stack

ASP.NET Core: The foundational framework for constructing the API, chosen for its scalability, performance, and cross-platform compatibility.
C#: The primary programming language utilized for backend development, providing a robust, statically-typed environment.
Entity Framework Core: Employs ORM capabilities for database interaction, ensuring seamless data access and manipulation.
JWT (JSON Web Tokens): Implements secure user authentication and authorization, enabling safe data transmission between parties.
Swagger/OpenAPI: Incorporates API documentation and testing functionalities, enhancing developer experience and facilitating client integration.
SQL Server/MySQL/PostgreSQL: Offers flexibility in database selection based on preferences or project requirements for storing product, user, and order data.
Image Processing Library (e.g., ImageSharp): Utilized for managing product images, enabling essential functionalities like upload, storage, and retrieval.
Git/GitHub: Serves as the version control system and collaborative platform for development, ensuring code integrity and facilitating collaboration.

## API Endpoints

The API provides the following endpoints:

Authorization endpoints for managing user authentication and authorization.
Product endpoints for retrieving products with optional filtering by category and name.
Product details endpoint for obtaining specific product information.
Cart management endpoints for adding items to the cart, removing items, and adjusting quantities.
Endpoint for placing orders, allowing submission of orders with product IDs and quantities.
Endpoint for viewing order history, enabling retrieval of past orders with relevant details such as ID, creation datetime, and total price.

## Setup Instructions

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd ecommerce-api`
3. Install dependencies: `dotnet restore`
4. Configure database connection in `appsettings.json`
5. Apply EF migrations: `dotnet ef database update`
6. Run the application: `dotnet run`

## API Documentation

Upon running the application, access the Swagger documentation by navigating to https://localhost:<port>/swagger in your preferred browser. This documentation provides comprehensive details about each endpoint, including request parameters and response schemas, facilitating testing and integration.

## Contribution Guidelines

Contributions are encouraged! Fork the repository, implement changes, and submit pull requests adhering to the existing code style and guidelines.

## License

This project is licensed under the MIT License. Refer to the LICENSE file for additional information.
