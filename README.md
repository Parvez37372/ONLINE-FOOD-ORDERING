online-pizza-order/
├── admin/               # Admin dashboard (Add/Edit/Delete Pizza, Manage Orders)
├── user/                # User side (Menu browsing, cart, checkout)
├── assets/              # Images, CSS, JS
├── db/                  # SQL schema or connection setup
├── config.php           # Database connection
└── README.md            # You're here!
👥 Roles
🧑‍💼 Admin Panel
Login: admin@example.com / admin123

Manage Pizza Menu (Add/Edit/Delete)

View Orders placed by users

Change Order Status (e.g., Pending, Preparing, Delivered)

Manage Users (optional)

🧑‍🍳 User Panel
Register/Login

Browse Menu

Add Pizzas to Cart

Place Order (Cash on Delivery / Online Payment)

View Order Status

🔧 Tech Stack
Frontend: HTML, CSS, JavaScript, Bootstrap

Backend: PHP

Database: MySQL/MariaDB

Server: XAMPP / WAMP (localhost)

📦 Features
✅ User Features
User Registration & Login

Pizza catalog with images, description, and prices

Cart system

Checkout & Order placement

Order status tracking

Contact/Support form

✅ Admin Features
Secure admin login

Add/Edit/Delete Pizza items

View all user orders

Change order status

View registered users

🖼️ Screenshots
Add screenshots like:

Login Page

User Menu Page

Admin Dashboard

Order Management

⚙️ Setup Instructions
Requirements:
PHP >= 7.4

MySQL

Apache Server (use XAMPP/WAMP)

Steps:
Clone or Download the repository.

Start Apache and MySQL via XAMPP.

Import the database from db/pizza_order.sql into phpMyAdmin.

Configure DB credentials in config.php.

php
Copy
Edit
// config.php
$host = "localhost";
$user = "root";
$pass = "";
$db = "pizza_order";
Open browser:

User: http://localhost/online-pizza-order/user/

Admin: http://localhost/online-pizza-order/admin/

🔐 Default Login Details (for testing)
Admin:

Email: admin@example.com

Password: admin123

User:

Email: user@example.com

Password: user123

(You can register a new user as well.)

✍️ Contribution
Want to contribute? Pull requests are welcome! Please fork the repo and submit changes.

📜 License
This project is open-source. Use freely for learning or personal projects.

Would you like me to generate the files for this project too (admin/index.php, user/index.php, etc.)?



