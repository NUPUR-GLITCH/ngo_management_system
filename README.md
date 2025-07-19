
# NGO Management System

This repository contains the **NGO Management System**, a comprehensive web application built with **pure PHP** and **MySQL** (SQL) for the backend. It is designed specifically for deployment and local development using **XAMPP**. The system helps NGOs manage operations efficiently, including projects, donors, beneficiaries, volunteers, events, finances, and reporting.

## Features

- **Project Management:** Create, monitor, and update projects.
- **Donor Management:** Track donor information, donations, and generate receipts.
- **Beneficiary Management:** Manage details of beneficiaries and their support history.
- **Volunteer Management:** Recruit, schedule, and coordinate volunteers.
- **Event Management:** Organize and manage events and campaigns.
- **Financial Tracking:** Monitor income, expenses, and generate financial reports.
- **User Roles:** Different roles for admins, staff, and volunteers.
- **Reporting:** Generate various reports for transparency and impact assessment.

## Technologies Used

- **Backend:** PHP (no framework)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** MySQL (SQL)
- **Web Server:** Apache (via XAMPP)

## Getting Started

### Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html) installed on your system (includes Apache and MySQL)
- Web browser

### Installation

1. **Clone or Download the repository:**
   - Download the ZIP or run:
     ```bash
     git clone https://github.com/NUPUR-GLITCH/ngo_management_system.git
     ```
   - Copy the `ngo_management_system` folder into your `xampp/htdocs` directory.

2. **Set up the Database:**
   - Start **Apache** and **MySQL** from the XAMPP Control Panel.
   - Open [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   - Create a new database (e.g., `ngo_management`)
   - Import the provided SQL file (if available) into the new database.  
     *(File might be named `ngo_management.sql` in the root directory or `/database` folder)*

3. **Configure Database Connection:**
   - Open the `config.php` file (or similar) in the project root or `includes` folder.
   - Update database connection details as needed (usually host, username, password, and database name).

4. **Run the Application:**
   - Visit [http://localhost/ngo_management_system](http://localhost/ngo_management_system) in your browser.

### Usage

- Login as admin, staff, or volunteer to access respective features.
- Use the navigation menu to manage projects, donors, beneficiaries, volunteers, events, financials, and reports.

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements or bug fixes.

1. Fork the repository.
2. Create a new branch for your feature/fix.
3. Commit your changes and push to your fork.
4. Open a Pull Request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any queries or support, please create an issue or contact the maintainer: [NUPUR-GLITCH](https://github.com/NUPUR-GLITCH)
