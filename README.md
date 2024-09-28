# 📚 E-Library Management System

An automated and efficient system built using **Flask** and **Celery**, designed to manage an E-Library's key functionalities such as daily user reminders, monthly reports, eBook data exports, and email notifications. This project demonstrates task automation, database querying, and email integration, creating a seamless experience for both users and administrators.

## 🚀 Features
- **Automated Tasks with Celery**: Daily reminders and monthly reports are handled via background jobs, improving efficiency.
- **eBook Data Exports**: Export eBook data in CSV format for easy backup and reporting.
- **Email Notifications**: Integrated email system for sending user notifications using Jinja2 templating.
- **User Roles & Security**: Managed user roles with **Flask-Security** to control access and permissions.
- **Database Operations**: Seamless database interactions using **SQLAlchemy**.

## 🛠️ Technologies Used
- **Flask**: Web framework for Python.
- **Celery**: Task queue for handling asynchronous tasks.
- **SQLAlchemy**: ORM for handling database operations.
- **Flask-Security**: Simple integration for security and authentication.
- **Jinja2**: Templating engine for generating HTML emails.
- **CSV**: Export eBook data in CSV format.
