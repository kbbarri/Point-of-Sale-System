# Basic POS System

A simple Point-of-Sale (POS) website created using CodeIgniter 4.

## Features

- Home page
- About page
- Customer Accounts page
- User Accounts page
- Static PHP arrays for customer and user data
- Navigation between all pages

## Technologies Used

- PHP
- CodeIgniter 4
- HTML
- Composer

## Installation

1. Clone the repository.

2. Open the project folder in VS Code.

3. Install the required dependencies:

   composer install

4. Copy the `env` file and rename the copy to `.env`.

5. Set the base URL in `.env`:

   app.baseURL = 'http://localhost:8080/'

6. Start the CodeIgniter development server:

   php spark serve

7. Open your browser and go to:

   http://localhost:8080/

## Pages

- `/` - Home
- `/about` - About
- `/customers` - Customer Accounts
- `/users` - User Accounts
