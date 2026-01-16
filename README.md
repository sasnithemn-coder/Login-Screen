Internal Login System – Case Study

Overview

This project implements a simple login and registration flow for an internal employee-only web application, designed as part of a UI/UX-focused case study.

The goal is to ensure only authenticated employees can access internal content, while keeping the experience clear and friendly.

Supported Users

Existing Employee – logs in using email and password
New Hire – registers and logs in for the first time

Features Implemented

Employee registration with validation
Secure login using email & password
Clear feedback for:
    Missing inputs
    Incorrect credentials
    Password mismatch
Dashboard page displaying logged-in user details
Logout functionality
Session persistence using localStorage

Assumptions

This is an internal system, not public signup
Credentials are mocked and stored client-side
Focus is on UX and flow, not production security
Users remain logged in until they log out

Design Priorities

Clear user guidance
Simple and intuitive interaction
Graceful error handling
Visibility of login state

Future Improvements

Backend-based authentication
Password hashing
Session expiration
Inline error messages instead of alerts
Role-based access control