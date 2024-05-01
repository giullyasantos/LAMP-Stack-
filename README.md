# LAMP-Stack "THE REEF"

The Reef is a water-themed contact management web application built on the LAMP stack. It provides features to manage contacts efficiently. Users can sign up, log in, add, delete, edit, and search contacts. They can also manage their profiles, including editing and deleting their user accounts.

Features:
- User signup and login
- Add, edit, and delete contacts
- Search for contacts
- Edit and delete user accounts
  
Technology Stack:
- Linux: The operating system running the application.
- Apache: The web server used to serve the application.
- MySQL: The database used to store user and contact data.
- PHP: The server-side scripting language used to build the application logic.

User Management:
- Signup: New users can register by filling out the signup form.
- Login: Registered users can log in to access the dashboard.
  
Contact Management:
- Add Contact: Use the "Add Contact" form to create a new contact.
- Edit Contact: Modify contact details by clicking the "Edit" button.
- Delete Contact: Remove contacts with the "Delete" button.
- Search Contacts: Use the search bar to find contacts based on name or other details.

Installation:

Server Setup:
- Install Apache, MySQL, and PHP on your Linux server.
- Instructions vary based on your Linux distribution. On Ubuntu, use sudo apt-get install apache2 mysql-server php php-mysql.
- 
Database Setup:
- Create a new MySQL database and tables for users and contacts.
- Modify the database configuration file (config.php) with your MySQL credentials.
- Deploy the Application:
- Clone the repository into your Apache server's document root (/var/www/html).
- Restart Apache to ensure the application is served correctly: sudo systemctl restart apache2.
- 
Access the Application:
- Open a web browser and navigate to http://localhost or your server's IP address.
