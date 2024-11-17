# Product REST API

This project is a Product REST API built using Spring Boot and Spring JPA. It allows users to create, update, retrieve, and delete products in a database. The API follows RESTful design principles, and all the endpoints use proper naming conventions as outlined in the assignment guidelines.

## Features:
1. **Create Product**: Add a new product to the database using the POST method.
2. **Retrieve All Products**: Get all products in the database using the GET method.
3. **Retrieve Product by ID**: Get a specific product using its ID with the GET method.
4. **Update Product**: Modify an existing product using the PUT method.
5. **Delete Product**: Remove a product from the database using the DELETE method.

## Implementation Details:
- The `Product` entity represents the products in the database.
- A `ProductRepository` was created to handle all database operations.
- A `ProductController` handles the REST endpoints and interacts with the repository.
- All endpoints were tested using Postman to verify proper functionality.

## Endpoints:
1. **POST /api/v1/products** - Create a new product.
2. **GET /api/v1/products** - Retrieve all products.
3. **GET /api/v1/products/{id}** - Retrieve a product by ID.
4. **PUT /api/v1/products/{id}** - Update an existing product by ID.
5. **DELETE /api/v1/products/{id}** - Delete a product by ID.

## Database:
- The program uses a MySQL database to store product data.
- The database connection details were configured in the `application.properties` file.