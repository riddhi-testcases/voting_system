# Voting Management System

## Overview
The **Voting Management System** is a web-based application built using **PHP, JavaScript, and SQL**. It provides an efficient and secure platform for conducting elections, allowing administrators to manage elections and voters to cast their votes electronically.

## Features
### Admin Panel:
- Secure admin authentication.
- Create and manage elections.
- Add, update, and delete candidates.
- View and manage registered voters.
- Monitor and view election results in real-time.

### Voter Panel:
- Secure voter authentication.
- View available elections and candidates.
- Cast votes securely.
- View voting history and results (if enabled by the admin).

## Technologies Used
- **Frontend**: JavaScript, HTML, CSS
- **Backend**: PHP
- **Database**: MySQL

## Installation Guide
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-repo/voting-management-system.git
   ```
2. **Setup Database**
   - Import the provided `database.sql` file into MySQL.
   - Configure database credentials in `config.php`.
3. **Run the Project**
   - Start Apache and MySQL using XAMPP or WAMP.
   - Place the project folder in the `htdocs` directory.
   - Access the system via `http://localhost/voting-management-system`.

## Usage
- **Admin Login**: Navigate to the admin login page and enter credentials.
- **Voter Login**: Register or log in as a voter to participate in elections.

## Security Features
- Encrypted passwords for secure authentication.
- Input validation to prevent SQL injection and XSS attacks.
- Role-based access control for administrators and voters.




