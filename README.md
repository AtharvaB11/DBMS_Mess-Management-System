# Mess Management System 🍲

This Mess Management System is built using XAMPP, PHP, and MySQL. It allows students to view the menu of the mess and enables the admin (owner of the mess) to manage and update the menu dynamically. The system utilizes several PHP classes such as Category, Item, Order, Table, Tax, and User, each with associated actions for managing their respective entities.

## Features 🌟

**Student Interface:**
- View daily menu offerings.
- Place orders.
- View order history.

**Admin Interface:**
- Add, edit, or remove menu categories and items.
- Manage user accounts and permissions.
- View and manage orders.
- Apply taxes to orders.

## Technologies Used 🛠️

- **XAMPP:** Local web server solution stack.
- **PHP:** Server-side scripting language.
- **MySQL:** Relational database management system.

## Installation 🚀

1. **Import Database:**
   - Import the `database.sql` file located in the `database/` directory to set up the database schema and initial data.

2. **Configure Database Connection:**
   - Open `config/database.php`.
   - Update the database connection parameters (`DB_HOST`, `DB_USER`, `DB_PASS`, `DB_NAME`) according to your XAMPP MySQL setup.

3. **Start XAMPP:**
   - Start Apache and MySQL modules in your XAMPP control panel.

4. **Access the Application:**
   - Open your web browser and navigate to `http://localhost/mess-management-system`.

## Usage 🚦

- **Student:**
  - Login with your credentials to view the menu and place orders.
  
- **Admin:**
  - Login with admin credentials to access the admin panel.
  - Manage menu categories, items, users, orders, and taxes through intuitive interfaces.

