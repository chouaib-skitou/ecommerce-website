
# Laravel E-commerce Website Project

## Introduction

This project was developed as part of our studies and the preparation of the University Diploma of Technology at the École Normale Supérieure de Marrakech. It represents our final year project, giving us the opportunity to apply the skills acquired during our two years of training and to gain new ones. These skills will help us define our professional projects, whether in further studies or launching our careers after the DUT.

## Project Overview

Our project is to create an e-commerce website, with the aim of finding solutions for several stores (online or local) such as the management of customer accounts, products, orders, promotions, and also effectively presenting the products offered by each store through an online catalog.

## Team Members

- SKITOU Chouaib
- ELHAID Oussama

## Technologies Used

- HTML
- CSS
- Bootstrap
- JavaScript
- Laravel 7
- MySQL

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone laravel-ecommerce-website
   ```

2. **Navigate to the project directory**:
   ```bash
   cd laravel-ecommerce-website
   ```

3. **Install Composer Dependencies**:
   ```bash
   composer install
   ```

4. **Install NPM Dependencies**:
   ```bash
   npm install
   ```

5. **Create a copy of your .env file**:
   ```bash
   cp .env.example .env
   ```

6. **Generate an app encryption key**:
   ```bash
   php artisan key:generate
   ```

7. **Create an empty database for the application**.

8. **In the .env file, add database information to allow Laravel to connect to the database**.

9. **Migrate the database**:
   ```bash
   php artisan migrate
   ```

10. **Seed the database (if necessary)**:
    ```bash
    php artisan db:seed
    ```

11. **Run the project**:
    ```bash
    php artisan serve
    ```

## Additional Notes

- Make sure to check the Laravel and PHP version requirements for Laravel 7.
- Adjust the database configuration in the .env file according to your local settings.
- For more detailed instructions or project-specific commands, refer to the Laravel documentation.
