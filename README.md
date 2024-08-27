

---

# Ghadade-Furniture

## Overview
**Ghadade-Furniture** is a web-based e-commerce application designed to create a user-friendly furniture store. It allows customers to browse and purchase furniture online, offering a seamless shopping experience. The application also securely stores customer data for authentication purposes.

## Features
- **User-Friendly Interface**: Easy navigation and intuitive design.
- **Secure Authentication**: Stores customer data securely for login.
- **Online Shopping**: Browse and purchase furniture directly from the website.

## Technologies Used
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: PHP
- **Database**: MySQL

## Setup Instructions

### Prerequisites
- **XAMPP Server** (for local server environment)
- Any web browser

### Running Locally
1. Clone or download the project and place it in the `htdocs` folder where XAMPP is installed.
2. Open the XAMPP control panel and start **Apache** and **MySQL**.
3. Open **PHPMyAdmin** and create a database named `furniture_store`.
4. Execute the following SQL query to create the `user` table:

    ```sql
    CREATE TABLE user (
        email VARCHAR(20) PRIMARY KEY, 
        name VARCHAR(20), 
        password VARCHAR(20), 
        phoneno INT, 
        address VARCHAR(50)
    );
    ```

5. Open your web browser and type `localhost/`, then navigate to the project path from `htdocs` in the address bar.

