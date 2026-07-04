# Tichi
# Tichi Authentication Automation Using Playwright

## About the Project

This project is a beginner-level automation testing project developed using Playwright and JavaScript.

The main aim of this project is to automate some of the basic authentication functionalities of the Tichi web application such as Login and Signup.

This project helped me understand how automation testing works and how Playwright can be used to automate web applications.

---

## Objective

The objective of this project is to learn Playwright by automating basic authentication scenarios and understanding the workflow of web application testing.

---

## Tools Used

- Playwright
- JavaScript
- Node.js
- Visual Studio Code

---

## Project Structure

```
Automation-Testing-Using-Playwright-main

│
├── PlaywrightLoginAutomation
│ ├── LoginPage.js
│ └── SignUpPage.js
│
├── test
│ ├── login.spec.js
│ ├── signup.spec.js
│ └── test.spec.js
│
├── playwright.config.js
├── package.json
└── README.md
```

---

## Test Scenarios

This project includes automation for the following scenarios:

### Login

- Login using registered email
- Invalid email validation
- Empty email validation

### Signup

- New user registration
- Existing user validation
- Required field validation

---

## What I Learned

While doing this project, I learned:

- Basics of Playwright
- Page Object Model (POM)
- Writing simple automation scripts
- Finding web elements using locators
- Executing Playwright test cases
- Understanding authentication workflow

---

## How to Run the Project

Install the required packages

```bash
npm install
```

Install Playwright browsers

```bash
npx playwright install
```

Run all tests

```bash
npx playwright test
```

Run Login tests

```bash
npx playwright test login.spec.js
```

Run Signup tests

```bash
npx playwright test signup.spec.js
```

---

## Report

After execution, Playwright generates an HTML report which can be viewed using:

```bash
npx playwright show-report
```

---

## Conclusion

This project helped me understand the basics of web automation testing using Playwright. It also gave me practical experience in automating authentication features like Login and Signup while learning the Page Object Model approach.

---

## Author

**Harish S**

BE - Electronics and Communication Engineering

Sri Shakthi Institute of Engineering and Technology
