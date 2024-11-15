Real-Time Order Tracking System (RTOTS)
A mini project created as part of the DBMS coursework at PES University for enabling real-time tracking of customer orders, ensuring transparency, streamlined operations, and enhanced customer satisfaction. This platform allows customers to place orders, track delivery status, and manage profiles, while providing administrators with tools to manage orders, update statuses, monitor inventory, and coordinate delivery.

Features
Customer Features
User Authentication: Secure login for customers and administrators with registration options.
Order Management: Customers can browse products, place orders with special instructions, and manage order history.
Real-Time Tracking: Track the status and location of deliveries in real-time.
Profile Management: Update personal information and manage multiple contact numbers.
Referral System: Invite other customers and track referrals.
Admin Features
Dashboard Overview: View statistics for active, in-transit, and delivered orders.
Order Tracking & Updates: Monitor and update order locations and statuses in real time.
Inventory Management: Track product availability and manage stock levels.
System Notifications: Alert users about updates and successful operations.
Technology Stack
Backend: Python (Flask Framework)
Frontend: HTML, CSS, JavaScript
Database: MySQL (including MySQL Workbench for database modeling)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/RTOTS.git
cd RTOTS
Install dependencies: Make sure you have Python and MySQL installed. Then install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Database Setup:

Import the Order_Tracking.sql file into MySQL Workbench to create the database schema and necessary tables.
Configure the database connection details in the Flask application.
Run the application:

bash
Copy code
flask run
Access the application: Open your browser and navigate to http://localhost:5000.

Usage
Customers: Register or log in to browse products, place orders, and track delivery status.
Administrators: Log in to access the admin dashboard, manage orders, update delivery statuses, and monitor inventory.
Project Structure
app/: Contains the main application files.
static/: CSS and JavaScript files for frontend styling and interactivity.
templates/: HTML templates for the frontend.
Order_Tracking.sql: Database schema file.
Contributing
Feel free to open issues and submit pull requests. Contributions are welcome!

License
MIT License

