# GPTL Bank - Quality Assurance Project

## Project Overview
**GPTL Bank** is my first hands-on project as a **Quality Assurance (QA) Tester**.  
The project focuses on validating the core functionalities of a banking system, including customer account creation and management, ensuring data integrity and proper error handling.

## Features Tested
- Creating new customer accounts  
- Adding and managing customer information  
- Input data validation  
- Handling invalid or non-existent data  

## Tools & Techniques
- **Microsoft Excel**: for documenting Test Cases and Bug Reports  
- **Manual Testing**: to verify functional requirements and system behavior  

## Test Case Documentation
Comprehensive **Test Cases** were developed to ensure:  
- Accuracy and validity of user inputs  
- Proper error messages for invalid operations  
- Functional workflows operate as expected  

**Sample Test Case:**  
- **TC_ID:** TC_NA_004  
- **Feature:** New Account  
- **Description:** Verify that opening a new account isn’t possible with data that doesn’t exist  
- **Preconditions:**  
  1. Manager should be logged in  
  2. New Account page should be opened  
- **Test Steps:**  
  1. Fill the customer ID with data that doesn’t exist  
  2. Choose a suitable type for the account  
  3. Fill the initial deposit field with valid data  
  4. Click on Submit  
- **Test Data:**  
  - Customer ID: `123456`  
  - Account type: `Saving`  
  - Initial deposit: `5000`  
- **Expected Result:** The system should show an error message: `"The customer ID doesn't exist"`  
- **Actual Result:** `"This page isn’t working right now. demo.guru99.com can't currently handle this request."`  
- **Status:** FAIL  

## Bugs & Issues
All identified bugs were recorded in a **Bug Report Sheet**, including detailed descriptions, steps to reproduce, and expected versus actual results.

## Author
**Sohaila Elabasy**  
Software Tester  
📧 sohailaismail6@gmail.com
