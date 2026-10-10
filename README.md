# UniResolve – University Complaint Management System

UniResolve is a web-based complaint management system designed to help university students submit complaints and track their resolution status. It provides a centralized platform for admins and staff members to manage, assign, and resolve complaints efficiently.

## Features

* **User Authentication** – Registration and login system.
* **Role-Based Access Control** – Separate access for Students, Admins, and Staff.
* **Complaint Submission** – Students can submit complaints easily.
* **Complaint Management** – Admins can view and manage all complaints.
* **Complaint Assignment** – Admins can assign complaints to staff members.
* **Status Tracking** – Track complaints through Pending, In Progress, and Resolved statuses.
* **User Management** – Manage system users and their roles.
* **Category Management** – Organize complaints by category.
* **Search and Filtering** – Find complaints efficiently.
* **Form Validation** – Validate user input.
* **AJAX Operations** – Support asynchronous communication.
* **JSON Data Handling** – Handle data using JSON where applicable.
* **MVC Architecture** – Organize the application using Model-View-Controller.

## Technology Stack

| Technology | Purpose                   |
| ---------- | ------------------------- |
| HTML       | Page structure            |
| CSS        | Styling                   |
| JavaScript | Client-side functionality |
| PHP        | Server-side development   |
| MySQL      | Database management       |
| AJAX       | Asynchronous requests     |
| JSON       | Data exchange             |
| MVC        | Application architecture  |

## User Roles

### Student

* Register and log in.
* Submit new complaints.
* View submitted complaints.
* Track complaint status.

### Admin

* View and manage all complaints.
* Manage users and complaint categories.
* Assign complaints to staff members.
* Update complaint status.

### Staff

* View assigned complaints.
* Access complaint details.
* Update complaint progress.
* Mark complaints as resolved.

## Complaint Workflow

Student → Submit Complaint → Admin → Assign to Staff → Staff → Resolve Complaint

## Complaint Status

* **Pending** – The complaint is awaiting action.
* **In Progress** – The complaint is being handled.
* **Resolved** – The complaint has been resolved.

## Project Structure

The project follows the MVC (Model-View-Controller) architecture to separate application logic, data handling, and presentation.

* `Model/` – Data handling and application logic.
* `View/` – User interface and presentation files.
* `Controller/` – Request handling and application flow.

*Note: Update the folder descriptions above if your actual project structure differs.*

## Installation and Setup

1. Install [XAMPP](https://www.apachefriends.org/).
2. Clone this repository into your XAMPP `htdocs` directory.
3. Start Apache and MySQL from the XAMPP Control Panel.
4. Create the required MySQL database using phpMyAdmin.
5. Import the project's database SQL file, if available.
6. Configure the database connection in the project.
7. Open the application in your browser using the appropriate local URL.

## Project Objectives

* Develop a practical university complaint management system.
* Implement role-based access and complaint workflows.
* Practice PHP, MySQL, JavaScript, AJAX, and JSON.
* Apply MVC architecture in web application development.

## Future Improvements

* Email notifications for complaint status updates.
* Complaint priority levels.
* Complaint history and activity logs.
* Dashboard statistics and reports.
* Improved security and user experience.

## License

This project is developed for educational purposes.

---

**UniResolve** – Making university complaint management simpler and more organized.

## Screenshots

### Home Page

![Home Page](assets/screenshots/home.png)

### Authentication

| Login | Registration |
|---|---|
| ![Login](./assets/screenshots/login.png) | ![Registration](./assets/screenshots/register.png) |

### Student Portal

| Student Dashboard | My Complaints |
|---|---|
| ![Student Dashboard](assets/screenshots/student-dashboard.png) | ![Submit Complaints](assets/screenshots/submit-complaints.png) |

### Admin Portal

| Admin Dashboard | Manage Users |
|---|---|
| ![Admin Dashboard](assets/screenshots/admin-dashboard.png) | ![Manage Complaints](assets/screenshots/manage-complaints.png) |

### Staff Portal

| Staff Dashboard | Assigned Complaints |
|---|---|
| ![Staff Dashboard](assets/screenshots/staff-dashboard.png) | ![Update Status](assets/screenshots/update-status.png) |

### Profile

![Profile](assets/screenshots/profile.png)
