
# The Gallery Cafe Web Development Project

## Project Overview
The **Gallery Cafe** website is designed to provide a seamless and interactive experience for customers and staff. The website includes features for table reservations, pre-orders, event promotions, and more. It has separate interfaces for admins, operational staff, and customers, each with specific permissions and capabilities. 

### Key Features:
- **Table Reservation System**: Allows users to book tables based on availability and restaurant capacity.
- **Pre-order System**: Customers can select food and beverages from a menu to pre-order before visiting.
- **User Authentication**: Admins and operational staff can log in with their credentials to manage the system, while customers can register and log in to make reservations or pre-orders.
- **Event and Promotion Page**: Displays events and promotions with easy booking options.
- **Admin Dashboard**: Admins can add, update, delete, and manage food items in the menu and view reservations and pre-orders.
- **Responsive Design**: The website is mobile-friendly and adapts to various screen sizes.

## Technologies Used:
- **HTML**: Structure of the website, creating web pages with forms, menus, tables, and more.
- **CSS**: Styling the website with a modern and user-friendly design. Color scheme: `#443229`, `#bca08b`, `#495057`.
- **JavaScript**: Client-side interactivity for dynamic elements, such as form validation, and interactive features like modals.
- **PHP**: Server-side scripting for user authentication, database management, and dynamic content generation.
- **MySQL**: Database for managing user information, reservations, pre-orders, and food items.

## Project Structure:
The project is organized into several files and folders to ensure clear separation of concerns:

1. **index.html**: The landing page of the website.
2. **register.html**: A form where customers can register their accounts.
3. **login.html**: A form for users to log in to their accounts.
4. **manage_food_beverage.php**: Admin panel for managing food and beverage items.
5. **add_food_item.php**: A form for admins to add new food and beverage items.
6. **table_reservation.php**: Allows customers to reserve a table based on capacity.
7. **pre_order.php**: Enables customers to select food and beverages to pre-order.
8. **admin_dashboard.php**: Admin interface for viewing reservations and pre-orders.
9. **includes/**: Contains reusable components like header, footer, and database connection (`connection.php`).
10. **css/**: Contains the stylesheets used for the website.
11. **js/**: Contains JavaScript files for client-side interactivity.

## Getting Started:

To run the project on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mohrashard/gallery-cafe-web.git
   ```

2. **Navigate to the project folder**:
   ```bash
   cd gallery-cafe-web
   ```



## Example Usage:

1. **Table Reservation**:
   - Navigate to the `table_reservation.php` page.
   - Select the number of people and preferred time.
   - The system will show available tables based on the reservation details.

2. **Pre-order**:
   - Go to `pre_order.php`, select food items from the menu, and submit the order.
   - The pre-order information will be saved in the database for staff to process.

3. **Admin Dashboard**:
   - Admins can log in with their credentials (`username: admin`, `password: admin123`).
   - Once logged in, they can manage food and beverage items, update menu categories, and view all reservations and pre-orders.


## How to Contribute:

1. Fork the repository
2. Create a new branch for your feature (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Create a pull request





### Notes:
- Replace `https://github.com/your-username/gallery-cafe-web.git` with the actual repository URL.
- You can add screenshots or other media in the appropriate section if needed.
- Adjust any paths or filenames as per your project structure.

This should cover everything from setting up the project to explaining key components. Let me know if you need further adjustments!
