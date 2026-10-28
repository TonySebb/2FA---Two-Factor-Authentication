# Two-Factor Authentication System

## Overview

This project is a Python Django-based authentication system that demonstrates two-factor authentication mechanisms.

## Features

* User registration and login
* OTP-based verification
* Email-based authentication
* Physical USB key authentication
* Encrypted file handling
* SQLite database integration

## Technologies Used

* Python
* Django
* SQLite
* Cryptography
* HTML, CSS, and JavaScript (if used in the project)

## Installation

1. Clone or download this repository.

2. Open the project folder in a terminal.

3. Create and activate a Python virtual environment.

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Configure the required environment variables and email settings.

6. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

7. Start the development server:

   ```bash
   python manage.py runserver
   ```

8. Open `http://127.0.0.1:8000/` in your browser.

## Notes

This project is intended for learning and demonstration purposes. Review the security configuration before using it in a production environment.
