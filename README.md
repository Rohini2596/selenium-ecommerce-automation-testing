# E-commerce UI Automation Testing using Selenium & Python

## Overview

This project automates core workflows of the SauceDemo e-commerce application using Selenium WebDriver and Python.

The automation suite validates critical user journeys including login, product addition to cart, and end-to-end checkout functionality.

## Tech Stack

* Python
* Selenium WebDriver
* Pytest
* Chrome Browser
* Selenium IDE

## Test Scenarios

### 1. Login Test

**Objective:** Verify successful login with valid credentials.

**Validation:**

* User enters username and password
* User clicks Login
* Products page is displayed

**Expected Result:**

* "Products" page loads successfully

---

### 2. Add To Cart Test

**Objective:** Verify product addition to shopping cart.

**Validation:**

* User logs in
* User adds Sauce Labs Backpack to cart
* User navigates to cart

**Expected Result:**

* Sauce Labs Backpack is present in cart

---

### 3. Checkout Test

**Objective:** Verify complete purchase workflow.

**Validation:**

* User logs in
* Adds product to cart
* Proceeds to checkout
* Enters shipping information
* Completes order

**Expected Result:**

* "Thank you for your order!" message is displayed

## Project Structure

```text
selenium-automation/
│
├── tests/
│   ├── test_login.py
│   ├── test_cart.py
│   └── test_checkout.py
│
├── requirements.txt
├── README.md
└── screenshots/
```

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd selenium-automation
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running Tests

Run Login Test:

```bash
python -m pytest tests/test_login.py -v
```

Run Cart Test:

```bash
python -m pytest tests/test_cart.py -v
```

Run Checkout Test:

```bash
python -m pytest tests/test_checkout.py -v
```

Run All Tests:

```bash
python -m pytest tests/ -v
```

## Test Results

| Test Case        | Status |
| ---------------- | ------ |
| Login Test       | Passed |
| Add To Cart Test | Passed |
| Checkout Test    | Passed |

## Skills Demonstrated

* Selenium WebDriver Automation
* Functional Testing
* End-to-End Testing
* Test Case Design
* UI Automation
* CSS Selector Identification
* Assertion-Based Validation
* Pytest Test Execution

## Future Improvements

* Implement Page Object Model (POM)
* Add HTML Reports
* Capture Screenshots on Failure
* Integrate Jenkins CI/CD Pipeline
* Expand Regression Test Coverage

```
```
