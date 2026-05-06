Book Store API

A simple REST API for managing books using Node.js, Express, MongoDB, and Mongoose.

Setup

1. Install dependencies
    npm install
2. Start server
    node server.js

API Endpoints

POST /books
GET /books
GET /books/:id
PUT /books/:id
DELETE /books/:id
GET /books/available

Sample Request

{
“title”: “Harry Potter”,
“author”: “J.K. Rowling”,
“price”: 500
}

Notes

* All fields are required except available
* Default value of available is true
* Price must be greater than 0
