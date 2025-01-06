# WattGuard - An Electricity Billing App

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
WattGuard is a web-based application designed to streamline electricity billing for administrators and customers. It automates bill generation, complaint management, and payment tracking, providing a user-friendly interface for both roles.

## Features
- **User Registration and Login:** Secure access for admins and customers.
- **Admin Dashboard:** Manage users, generate bills, and resolve complaints.
- **Customer Dashboard:** View bills, track payments, and file complaints.
- **Bill Generation:** Automatic calculation of electricity bills based on usage data.
- **Complaint Management:** Easy logging and resolution of complaints.
- **Online Payments:** Secure bill payments and receipt generation.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** XAMPP (Apache, MySQL, PHP)
- **Version Control:** Git (GitHub)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/regina-phalange-dev/WattGuard/wattguard.git
   ```
2. Install XAMPP on your system and start Apache and MySQL services.
3. Import the database:
   - Open phpMyAdmin.
   - Create a new database named `wattguard`.
   - Import the SQL file located in the `/db` directory of the project.
4. Configure database connection:
   - Edit the `config.php` file in the project root to match your MySQL credentials.
5. Start the local server:
   - Place the project folder in the `htdocs` directory of XAMPP.
   - Access the application at `http://localhost/wattguard`.

## Usage
### Admin Role
1. Log in to the admin dashboard.
2. Generate monthly bills for all customers.
3. View and resolve complaints.
4. Manage customer accounts and data.

### Customer Role
1. Register and log in to the customer dashboard.
2. View current and past bills.
3. Pay bills online securely.
4. File complaints and track their status.

## Project Structure
```
WattGuard/
├── css/            # Stylesheets
├── js/             # JavaScript files
├── db/             # Database schema and data
├── templates/      # HTML templates
├── config.php     # Database configuration
├── index.php      # Main entry point
├── README.md       # Project documentation
```

## Future Enhancements
- **Mobile App:** Extend functionality to mobile platforms.
- **Advanced Analytics:** Include detailed usage reports and predictions.
- **Third-Party Integrations:** Integrate with external payment systems.
- **Multi-Tier User Roles:** Add features for technicians and super admins.

## Contributing
We welcome contributions to enhance WattGuard. To contribute:
1. Fork the repository.
2. Create a new branch (`feature-name`).
3. Commit your changes.
4. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

