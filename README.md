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

<img width="1087" height="908" alt="Screenshot 2026-10-30 141156" src="https://github.com/user-attachments/assets/43872681-f97e-44f2-a5bc-53d1073807f4" />

<img width="1030" height="841" alt="Screenshot 2026-10-30 141210" src="https://github.com/user-attachments/assets/1df13fa7-41f4-4077-b45c-b30debdefa9d" />

<img width="1051" height="837" alt="Screenshot 2026-10-30 141253" src="https://github.com/user-attachments/assets/fe6aa1ba-1818-4007-b21c-08ddb33c2e1d" />

<img width="1040" height="831" alt="Screenshot 2026-10-30 141301" src="https://github.com/user-attachments/assets/d7fc2c52-e68d-4eaf-a6df-19d9a659478c" />

