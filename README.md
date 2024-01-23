Link to ppt:https://www.canva.com/design/DAFh9MtCgbc/trjHHWEMWzlfYtfJAqJKpA/edit

Overview

ZeroTrust is a web application built with Flask that focuses on secure user authentication and password management. It incorporates features like one-time password (OTP) verification, password strength checking, and personalized password recommendations.

Table of Contents

Installation

Usage

Features

Dependencies

Configuration


Installation

To run this Flask application locally, follow these steps:

1. Clone the repository:git clone https://github.com/kashish130/Zero_Trust_Password.git

2. Change into the project directory:cd Zero_Trust_Password

3. Install the required dependencies: pip install -r requirements.txt

4. Set up the MySQL database. Ensure you have a MySQL server running and update the db_config dictionary in the app.py file with your database credentials.

5. Run the Flask application: python app.py

Visit http://localhost:5000/ in your web browser to access the application.

Usage

The application provides several routes for user registration, login, and password management. Here are some key routes:

/: Welcome page

/login1: Login page

/signup1: Signup page

/password_checker_signup: Password strength checker for signup

/password_checker_login: Password strength checker for login

/sendOtp: Route for sending OTP

/signup_add: Additional information for signup

/submit_form: Form submission for user signup

/submit_signupform: Additional information submission for signup

/send_OTP: Sending OTP for login

/verify_otp: Verifying OTP

/password: Password strength checking for signup

/password_login: Password strength checking for login

/recommend: Password recommendation

/recommend_login: Password recommendation for login

Features

User Authentication: Secure user registration and login.

One-Time Password (OTP): OTP generation and verification for additional security.

Password Strength Checker: Evaluate the strength of a password based on various criteria.

Password Recommendation: Generate recommended passwords based on user information.

MySQL Database: Store user data securely in a MySQL database.

Dependencies

Flask

MySQL Connector

smtplib

Random

Math

Configuration

Update the db_config dictionary in the app.py file with your MySQL database credentials.





