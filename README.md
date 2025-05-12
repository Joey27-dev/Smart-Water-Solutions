# Smart Water Solutions

## Disclaimer

Please note that due to the limitations of **GitHub Pages**, this project cannot include backend functionality such as PHP scripts, MySQL integration, or server-side operations. **GitHub Pages** only supports static content (HTML, CSS, JavaScript). As a result, the backend features of this Smart Water Meter Solutions, including user authentication, data retrieval, and real-time water tracking, can only be experienced when running the project locally or on a live server with appropriate backend support (Apache, PHP, MySQL).

For full functionality, please follow the installation instructions above to run the project on your local machine with an Apache server and MySQL database.

Thank you for your understanding.

## Overview

This is a fully responsive **Smart Water Meter Web Portal** designed for owners and tenants to monitor their water usage. The app integrates with MySQL using PHP and runs on an Apache server. The portal features a secure login and signup system, dashboards for both tenants and owners, and real-time tracking of water usage.

### Key Features:
- **Responsive Design**: Fully optimized for both desktop and mobile devices.
- **Separate Dashboards**: Personalized dashboards for both owners and tenants with real-time water usage data.
- **Secure Login & Signup**: Fully protected login and signup systems using password hashing and session management.
- **Real-Time Water Usage Tracking**: Provides live data on water consumption and meter status.
- **MySQL Integration**: Manages data storage and retrieval.
- **Security Features**: Includes secure password hashing and session management.
- **Smooth Scroll Animations**: Enhances user experience with smooth transitions and scrolling effects.
- **Contact & FAQ**: Provides users with frequently asked questions and support contact details.

## Technologies Used

### Frontend:
- **HTML5**
- **CSS3**
- **JavaScript**
- **Bootstrap** (for responsive design)

### Backend:
- **PHP** (Server-side scripting)
- **MySQL** (Database management)
- **Apache Server** (For running PHP)

### Security:
- **Password Hashing** (Using PHP’s `password_hash` and `password_verify` functions)
- **Session Management** (Secure login sessions)

## Installation

### Prerequisites:
- Apache Server (with PHP support)
- MySQL database server
- A code editor (e.g., VSCode)
- A modern web browser (e.g., Chrome, Firefox)

### Steps to Run Locally:

1. **Set up Apache and MySQL:**
   Ensure Apache and MySQL are installed and running on your local machine. You can use **XAMPP** or **MAMP** for easy setup.

2. **Import the database:**
   - Open **phpMyAdmin** (or your MySQL client).
   - Create a new database (e.g., `smart_water_meter`).
   - Import the database schema (SQL file) to create necessary tables.

3. **Configure Database Connection:**
   - Navigate to the `config` directory and open `db_connect.php`.
   - Update the database connection settings (username, password, database name) to match your local environment.

4. **Launch the Project:**
   - Start the Apache server.
   - Open your browser and navigate to `http://localhost/smart-water-meter`.

5. **Access the Application:**
   - Use the provided login credentials or create a new account for testing.

## Project Structure

- **/assets**: Contains images, CSS files, and JavaScript files.
- **/config**: Includes database configuration and connection scripts.
- **/includes**: Contains reusable PHP functions and header/footer includes.
- **/public**: The main web folder with `home.html`, login, signup, and other user pages.
- **/php**: Handles backend logic for user authentication, data retrieval, and water meter management.
- **/sql**: Contains SQL scripts for setting up the database.

## Contact Author

**Joash Austin Pillay**  
[LinkedIn - Joash Pillay](https://www.linkedin.com/in/joashpillay) • [GitHub: Joey27-dev](https://github.com/Joey27-dev) • [Email: joashaustinpillay27@gmail.com](joashaustinpillay27@gmail.com)

---
