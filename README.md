# Bookstore API

A Node.js and Express API for managing a bookstore.

## Endpoints

### Get List of Books

- `GET /`: Get the list of books available in the shop.

### Get Book Details by ISBN

- `GET /isbn/:isbn`: Get book details based on ISBN.

### Get Books by Author

- `GET /author/:author`: Get book details based on the author's name.

### Get Books by Title

- `GET /title/:title`: Get book details based on the book title.

### Get Book Reviews

- `GET /review/:isbn`: Get book reviews based on ISBN.

### Register a New User

- `POST /register`: Register a new user.

### Login as a Registered User

- `POST customer/login`: Log in as a registered user.

### Add or Modify a Book Review

- `PUT customer/auth/review/:isbn`: Add or modify a book review.

### Delete a Book Review

- `DELETE customer/auth/review/:isbn`: Delete a book review.

## Usage

This API provides various endpoints for managing books and user reviews. You can use these endpoints to retrieve book information, add or modify reviews, register new users, and log in.

## Installation & Running

1. Clone the repository:

   ```
   git clone https://github.com/abnerl30/expressBookReviews.git

2. Navigate to the project directory:

   ```
   cd expressBookReviews

3. Navigate to the api directory:

   ```
   cd final_project

4. Install dependencies using npm:

   ```
   npm install

5. To start the API server, run the following command:

   ```
   npm start

The API will be accessible at http://localhost:5000.

## Contributing

Contributions are welcome. 

