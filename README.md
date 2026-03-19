# factorial-automation-tests
This repository contains Playwright automation tests for a factorial calculator web app, including UI validation, functional testing, and API verification.


# Factorial App Automation Tests

## Overview

This project contains automated tests for the Factorial web application:
http://qainterview.pythonanywhere.com

The tests were created as part of a QA assessment and cover UI functionality, validation, and API behaviour.

---

## Tools Used

* Playwright (JavaScript)
* Node.js

---

## Test Coverage

### 1. Functional Test

* Verify factorial calculation for valid input (e.g. 12 → 479001600)

### 2. Validation Test

* Verify behaviour when input is empty
* Check for validation styling (UI feedback)

### 3. API Test

* Verify request method (GET)
* Verify query parameter (number)
* Verify request headers
* Validate response correctness

---

## Project Structure

```
tests/
  factorial.spec.js
  validation.spec.js
  api.spec.js
```

---

## How to Run Tests

1. Install dependencies:

```
npm install
```

2. Run tests:

```
npx playwright test
```

---

## Notes

* Some tests may fail due to known defects in the application (e.g. missing validation styling)
* UI validation is limited by current application implementation

---

## Author

Lisbon Ramothwala

