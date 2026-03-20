 ** factorial-automation-tests**
 
This repository contains loadrunner tests for a factorial calculator web app, including UI validation, functional testing, and API verification.


Factorial App Automation Tests

Overview

This project contains automated tests for the Factorial web application:
http://qainterview.pythonanywhere.com

 

Tools Used

  Playwright (JavaScript)
  Node.js

 

Test Coverage

   1. Functional Test

Verify factorial calculation for valid input (e.g. 12 → 479001600)

   2. Validation Test

  Verify behaviour when input is empty
  Check for validation styling (UI feedback)

   3. API Test

  Verify request method (GET)
  Validate response correctness


How to Run Tests

1. Install dependencies:
loadrunner
2. Run tests:
VuGen

  Notes

  Some tests may fail due to known defects in the application (e.g. missing validation styling)
  UI validation is limited by current application implementation

 
 Author

Lisbon Ramothwala

