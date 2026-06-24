# Serverest API – Postman Collection

API test collection for the [Serverest](https://serverest.dev) REST API, built as part of a QA portfolio to demonstrate API testing skills using Postman.

## About the Project

This collection covers the core modules of the Serverest API: authentication, user management, product management, and cart operations. It includes environment configuration, dynamic variable management, and an automated token extraction script to support authenticated request flows.

## Collection Structure

| Folder | Requests |
|--------|----------|
| Login | POST Login |
| Users | POST Create User · GET Get All Users · GET Get User by ID |
| Products | POST Create Product · GET Get All Products · GET Get Product by ID · PUT Update Product · DELETE Delete Product |
| Cart | GET List Carts · POST Create Cart · GET Get Cart by ID · DELETE Checkout Cart · DELETE Cancel Cart |

**Total: 14 requests**

## Environment Setup

The collection uses a Postman Environment named **Serverest** with the following variables:

| Variable | Description |
|----------|-------------|
| `BASE_URL` | `https://serverest.dev` |
| `product_id` | Populated after creating a product |
| `cart_id` | Populated after creating a cart |
|