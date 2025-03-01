# eCommerce PHP Project

## Overview
The **eCommerce PHP Project** is a web-based application that allows users to browse products, add items to a cart, and complete transactions. It includes an admin panel for managing products, orders, and users.

## Features
- User authentication (Login/Register)
- Product listing and categories
- Shopping cart and checkout
- Order management
- Admin dashboard for managing products and users
- Payment gateway integration (if applicable)
- Responsive design

## Installation
### Prerequisites
Ensure you have the following installed:
- [PHP](https://www.php.net/downloads)
- [MySQL](https://www.mysql.com/downloads/)
- [Apache](https://httpd.apache.org/download.cgi) or [XAMPP](https://www.apachefriends.org/index.html)

### Steps
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/ecommerce-php.git
   cd ecommerce-php
   ```
2. **Move the project to your web server's root directory:**
   ```sh
   mv ecommerce-php /var/www/html/  # For Linux
   ```
   If using XAMPP, move it to `C:\xampp\htdocs\`.
3. **Import the database:**
   - Open `phpMyAdmin`.
   - Create a new database (e.g., `ecommerce_db`).
   - Import `database.sql` from the project folder.
4. **Configure the database connection:**
   - Edit `config.php` or `db.php` and set your database credentials:
   ```php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');
   define('DB_PASSWORD', '');
   define('DB_NAME', 'ecommerce_db');
   ```
5. **Run the project:**
   - Start Apache and MySQL in XAMPP.
   - Open a browser and go to `http://localhost/ecommerce-php/`.

## Usage
1. **User Registration & Login:** Create an account or log in.
2. **Browse Products:** View available products by category.
3. **Add to Cart & Checkout:** Select items and proceed to checkout.
4. **Admin Panel:**
   - Access at `http://localhost/ecommerce-php/admin/`
   - Default login: `admin / password` (update credentials in the database)

## Technologies Used
- PHP
- MySQL
- HTML, CSS, JavaScript
- Bootstrap (for styling)
- jQuery (for frontend interactions)

## Contributing
1. Fork the repository.
2. Create a new branch (`feature-xyz`).
3. Commit your changes.
4. Push to the branch and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, reach out at nangsengmi10@gmail.com.

