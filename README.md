# Tichi Authentication Testing

## Overview

This project focuses on manually testing the authentication module of the Tichi web application. The objective was to verify the functionality of Login, Signup, OTP Verification, and Forgot Password by creating test cases and identifying defects in the application.

The project includes a comprehensive set of test cases and a detailed bug report based on the testing performed.

---

## Project Objectives

- Understand the authentication workflow of the application.
- Create test cases for different authentication scenarios.
- Identify functional and usability defects.
- Document bugs with severity and priority.

---

## Modules Tested

- Login
- Signup
- OTP Verification
- Forgot Password
- Session Management
- Input Validation

---

## Deliverables

- Test Case Document (80 Test Cases)
- Bug Report
- Defect Summary

---

## Test Scenarios Covered

### Login

- Valid Login
- Invalid Email
- Empty Email
- Unverified Email
- Existing User Login

### Signup

- New User Registration
- Existing User
- Required Field Validation
- Invalid Email Format
- Password Validation

### OTP Verification

- Valid OTP
- Invalid OTP
- Expired OTP
- Resend OTP
- OTP Page Refresh
- OTP Countdown

### Forgot Password

- Password Reset
- Invalid Email
- Reset Link Validation

### Security & Session

- Multiple Browser Tabs
- Session Handling
- Unauthorized Access
- Browser Refresh

---

## Bugs Identified

Some of the issues identified during testing include:

- User gets stuck after leaving the OTP verification page.
- "Email Not Verified" workflow has no recovery option.
- OTP countdown timer does not update correctly.
- Refreshing the OTP page returns the user to the signup page.
- Internal Server Error observed during concurrent login testing.

---

## Tools Used

- Microsoft Excel (Test Case Documentation)
- Microsoft Excel (Bug Report Documentation)
- Google Chrome
- Tichi Web Application (Stage Environment)

---

## Learning Outcome

Through this project, I learned:

- Software Testing Fundamentals
- Writing Test Cases
- Bug Reporting
- Defect Classification
- Severity and Priority Analysis
- Authentication Workflow Testing

---

## Author

**Harish S**

BE – Electronics and Communication Engineering

Sri Shakthi Institute of Engineering and Technology
