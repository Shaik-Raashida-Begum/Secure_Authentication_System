# Secure Authentication System

## Project Overview
The Secure Authentication System is a web-based application developed using Python and Flask. It allows users to register, log in and securely access their accounts.

## Features
- User Registration
- User Login
- Password Hashing using bcrypt
- Session Management
- User Dashboard
- Logout Functionality
- SQLite Database Integration

## Technologies Used
- Python
- Flask
- HTML
- CSS
- SQLite
- bcrypt

## Project Structure
```text
Secure_Authentication_System/
│
├── app.py
├── requirements.txt
├── .gitignore
├── templates/
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
├── static/
│   └── style.css
└── README.md
```

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Open the project folder.

3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

4. Activate the environment on Windows:
   ```bash
   venv\Scripts\activate
   ```

5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

6. Create a `.env` file and configure your Flask secret key.

7. Run the application:
   ```bash
   python app.py
   ```

8. Open your browser:
   `http://127.0.0.1:5000`

## Security
- Passwords are stored using bcrypt hashing.
- User sessions are managed using Flask sessions.
- Environment secrets should not be committed to GitHub.

## Author
Developed as a Python Flask project.

### Output
