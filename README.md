# NewSonicSargam-Test-Case
 Sonic Sargam Login/Signup Page Testing
Introduction
This document summarizes the testing activities performed on the Login and Signup functionality of the Sonic Sargam website. The objective was to identify bugs, UI issues, and usability challenges, ensuring the system works correctly across different browsers and screen sizes.
# Sonic Sargam – Login/Signup Testing Project


##  Project Type
Testing (Manual) | Frontend Validation

##  Tested App URL
https://newsonicsargam.netlify.app/login.html

##  Directory Structure
test-report/
├─ test-plan.docx  
├─ test-cases.xlsx  
├─ defect-report.xlsx  
├─ screenshots/  
├─ readme.md  


##  Features Tested
- Login with valid/invalid credentials  
- Signup behavior and feedback  
- UI responsiveness and alignment  
- Input validation for email and password  
- Refresh/reset form behavior  
- Visibility of password input  
- Presence of alert/error messages  

##  Design Decisions & Assumptions
- The homepage should load after successful login.
- Empty input fields should disable the login button.
- Error messages should guide the user for incorrect entries.
- The UI should be responsive on all screen sizes.

## Installation & Getting Started
No installation required. Simply open the deployed app in a browser:

https://newsonicsargam.netlify.app/login.html

Test Summary
Functional Testing:

Verified login and signup flows with valid and invalid credentials.
Checked for redirection after successful login.
Observed validation behavior for empty fields and incorrect inputs.

UI Testing:
Evaluated the alignment of input fields and buttons.
Tested the page's responsiveness on various screen sizes and zoom levels.

Usability Testing:
Tesed visibility of password input.
Checked reset behavior on page refresh.
Looked for helpful alert messages and missing features like "Forgot Password".

 Key Bugs/Defects Identified
Priority	Issue Description
P0	No redirection to homepage after successful login
P0	No error shown for invalid email or password
P3	Login button is enabled even with empty input fields
P4	UI misalignment when zoomed
P3	Page is not responsive on different screen sizes
P2	Missing password visibility toggle

Mind Map (Structure Overview)
Login/Signup Module
Functional Testing
Valid/Invalid credentials
Error messages
Redirection
UI testing
Field/button alignment
Responsiveness
Usability Testing
Alerts and feedback
Refresh behavior
Missing features (toggle, forgot password)

 Feedback and Suggestions
Redirect user to homepage after successful login.
Add proper error messages for invalid login attempts.
Disable login button until both fields are filled.
Fix layout alignment issues.
Make page fully responsive for mobile and tablet users.
Add password visibility toggle for better UX.
Include "Forgot Password" link for account recovery.

Tested By
Name: Akash Yadav
Browser Used: Chrome
Device: Windows 10 Laptop
