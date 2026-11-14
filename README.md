🌍 Volunteer Community Portal

Connecting people. Empowering communities. Creating impact.

A web-based platform designed to bridge the gap between volunteers and community organizations. Volunteer Community Portal provides a centralized space where individuals can discover volunteering opportunities, participate in community initiatives, track their contributions, and connect with organizations working toward meaningful change.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/Flask-Web_Framework-black?logo=flask" />
  <img src="https://img.shields.io/badge/SQLite-Database-blue?logo=sqlite" />
  <img src="https://img.shields.io/badge/Deployment-Render-purple?logo=render" />
</p>---

✨ Overview

Volunteer Community Portal is built to make volunteering more accessible and organized. The platform allows volunteers to explore activities, join initiatives, record participation, and monitor their volunteering progress through a personalized dashboard.

Organizations can create and manage activities, while administrators oversee organization approvals and platform participation.

🚀 Features

👤 Volunteer Experience

- Account registration and secure authentication
- Personalized volunteer dashboard
- Browse available volunteering activities
- Join or leave activities
- Manage personal profile information
- Track volunteering hours and participation
- View volunteering activity details

🏢 Organization Management

- Organization account support
- Activity creation and management
- Attendance recording
- Volunteer participation management
- Organization approval workflow

🛡️ Administration

- Administrator authentication
- Review organization applications
- Approve or reject organizations
- Manage platform participation

🛠️ Built With

Technology| Purpose
Python| Backend programming
Flask| Web application framework
SQLite| Database storage
HTML5| Page structure
CSS3| Styling and responsive layouts
JavaScript| Client-side functionality
Gunicorn| Production application server
Render| Cloud deployment

📂 Project Structure

volunteer-community-portal/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── activities.html
│   └── ...
│
├── static/
│   ├── css/
│   │   ├── style.css
│   │   └── dashboard.css
│   ├── images/
│   │   └── ...
│   └── js
│
└── database.db

⚙️ Installation & Setup

Prerequisites

- Python 3.10+
- pip

1. Clone the Repository

git clone https://github.com/IBdaEdgerunnner/volunteer-community-portal.git
cd volunteer-community-portal

2. Create a Virtual Environment

python -m venv venv

Activate it:

Windows

venv\Scripts\activate

Linux/macOS

source venv/bin/activate

3. Install Dependencies

pip install -r requirements.txt

4. Run the Application

python app.py

Open your browser:

http://127.0.0.1:5000

The application initializes its SQLite database automatically.

☁️ Deployment

The application is deployed using Render.

Live Application:
https://volunteer-community-portal.onrender.com

Production Configuration

Set the following environment variable:

Variable| Description
"SECRET_KEY"| Secret key used to secure Flask sessions

The application is served using Gunicorn.

🔐 Security Notes

- User passwords are hashed before storage.
- Authentication is handled through Flask sessions.
- Database operations use parameterized queries.
- A secure production secret key should be configured through environment variables.

This project is an educational application and may require additional security hardening before production-scale use.

🎓 Project Purpose

Volunteer Community Portal was developed as an educational project demonstrating web application development, authentication, database integration, and community-oriented platform design.

---

<p align="center">
  <strong>Built to make volunteering easier and community impact greater.</strong>
</p>
