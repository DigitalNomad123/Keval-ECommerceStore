# ECommerceStore
Author: Keval Patel

Organization: ECommerceStore 



## Description

This project offers a RESTful service tailored for an E-Commerce platform, facilitating seamless item purchases using a pre-populated database. It comprises a .NET Core (C#) backend service equipped with the following functionalities:

   Utilization of an SQL/SQLite Server database featuring well-defined entities and established foreign key relationships.
    Incorporation of JWT token-based authentication for ensuring secure user access.
    Integration of Identity Framework to manage users, define roles, and enforce access controls.
    Activation of an email service triggered upon user registration to enhance user engagement.
    Implementation of robust authentication and authorization mechanisms.
    Adoption of git for version control to maintain codebase integrity and facilitate collaborative development.

This project serves as a fundamental backend solution for E-Commerce websites, offering a reliable framework to support user interactions, secure transactions, and system scalability.

## Usage
Checkout sample (Must be authenticated)
```json
{
  {
  "userProfile": {
    "firstName": "Keval",
    "lastName": "Test"
  },
  "shippingAddress": {
    "street": "25 Baker Street",
    "city": "London",
    "state": "",
    "country": "United Kingdom",
    "zipCode": "W1U 8EQ"
  },
  "billingAddress": {
    "street": "25 Baker Street",
    "city": "London",
    "state": "",
    "country": "United Kingdom",
    "zipCode": "W1U 8EQ"
  },
  "orderItems": [
    {
      "quantity": 2,
      "productId": 101
    },
    {
      "quantity": 1,
      "productId": 205
    }
  ]
}

```
