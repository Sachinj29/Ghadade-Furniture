# 🪑 Ghadade-Furniture

> A web-based **e-commerce furniture store** that allows users to browse, register, and purchase furniture online — designed with a focus on simplicity, usability, and secure customer management.

---

## 📌 Overview

**Ghadade-Furniture** is a user-friendly furniture store web application developed using **PHP**, **HTML/CSS**, and **MySQL**. Customers can explore products, register/login securely, and complete purchases in a seamless shopping experience.

---

## ✨ Features

- 🖥️ **User-Friendly Interface** — Clean layout with intuitive navigation  
- 🔐 **Secure Authentication** — User login and registration with password protection  
- 🛒 **Online Shopping** — Browse, view details, and purchase furniture items  

---

## 🧰 Technologies Used

| Layer      | Technology                   |
|------------|------------------------------|
| Frontend   | HTML, CSS, Bootstrap, JavaScript |
| Backend    | PHP                           |
| Database   | MySQL                         |
| Server     | XAMPP (Apache + MySQL)        |

---

## ⚙️ Setup Instructions

### ✅ Prerequisites

- ✅ Install [XAMPP](https://www.apachefriends.org/)
- ✅ Any modern web browser (Chrome, Firefox, etc.)

---

### 🧪 Running the Project Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/ghadade-furniture.git
   ```

2. **Move Project Folder**

   Copy the entire project folder into your XAMPP `htdocs` directory:

   ```
   C:/xampp/htdocs/ghadade-furniture
   ```

3. **Start Apache and MySQL**

   Open **XAMPP Control Panel** and start:
   - ✅ Apache
   - ✅ MySQL

4. **Setup the Database**

   - Go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   - Create a new database: `furniture_store`
   - Execute the following SQL query to create the user table:

     ```sql
     CREATE TABLE user (
         email VARCHAR(20) PRIMARY KEY,
         name VARCHAR(20),
         password VARCHAR(20),
         phoneno INT,
         address VARCHAR(50)
     );
     ```

5. **Access the Web App**

   - Open your browser
   - Go to:  
     ```
     http://localhost/ghadade-furniture/
     ```

---


