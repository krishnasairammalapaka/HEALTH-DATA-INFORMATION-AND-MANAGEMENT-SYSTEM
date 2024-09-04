Health Data Information and Management System
Overview
The Health Data Information and Management System is a web application designed to manage and analyze health data efficiently and securely. The application leverages Flask for the backend, MongoDB for the database, and Tailwind CSS for a modern and responsive frontend design. This project includes user and admin authentication, theme toggling, and a clean, user-friendly interface.

Features
User and Admin Authentication: Secure registration and login for users and admins.
Data Management: Store and manage user and admin data in MongoDB.
Responsive UI: Modern, responsive design using Tailwind CSS.
Theme Toggling: Light and dark theme support with cookie-based persistence.
Navigation: Easy navigation between pages such as Home, About Us, Facilities, and Sign In.
Tech Stack
Backend: Flask (Python)
Database: MongoDB
Frontend: HTML, CSS, Tailwind CSS
Theme Management: JavaScript with cookies
Project Structure
bash
Copy code
/health-data-system
├── /backend
│   ├── app.py
│   ├── requirements.txt
│   └── Procfile
└── /frontend
    ├── /static
    │   └── /css
    │       └── styles.css
    ├── /templates
    │   ├── home.html
    │   ├── aboutus.html
    │   ├── facilities.html
    │   └── signin.html
    └── app.py
Getting Started
Prerequisites
Python 3.x
Node.js and npm
MongoDB
