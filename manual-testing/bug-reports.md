#  Bug Reports

This document contains **sample bug reports** found during testing of the Login functionality.  
The bugs demonstrate understanding of **functional, validation, UI, UX, and localization issues**.

---

## BUG-SC-01: Login works with empty password

**Severity:** Major  
**Priority:** High  

### Preconditions
- User is on the Login page
- A valid username exists in the system

### Steps to Reproduce
1. Open the Login page  
2. Enter a valid username  
3. Leave the password field empty  
4. Click the **Login** button  

### Actual Result
- User is successfully logged in  

### Expected Result
- User should not be logged in  
- Validation error message should be displayed  

---

## BUG-SC-02: Missing error message after entering invalid credentials

**Severity:** Major  
**Priority:** Medium  

### Preconditions
- User is on the Login page  

### Steps to Reproduce
1. Open the Login page  
2. Enter an invalid username  
3. Enter an invalid password  
4. Click the **Login** button  

### Actual Result
- User is not logged in  
- No error message is displayed  

### Expected Result
- Error message indicating invalid credentials should be displayed  

---

## BUG-SC-03: UI and localization issues in login error message

**Severity:** Minor  
**Priority:** Medium  

### Preconditions
- User is on the Login page  

### Steps to Reproduce
1. Open the Login page  
2. Enter an incorrect password  
3. Click the **Login** button  

### Actual Result
- Error message has low contrast (light grey text on white background)  
- Error message text is partially cut off  
- Error message is displayed in English instead of Ukrainian  

### Expected Result
- Error message should be clearly readable  
- Text should be fully visible  
- Error message should be displayed in Ukrainian  

---

## BUG-SC-04: Login button is enabled when required fields are empty

**Severity:** Minor  
**Priority:** Low  

### Preconditions
- User is on the Login page  

### Steps to Reproduce
1. Open the Login page  
2. Leave the username field empty  
3. Leave the password field empty  

### Actual Result
- Login button is enabled and clickable  

### Expected Result
- Login button should be disabled until all required fields are filled  

---

## BUG-SC-05: Error message is not cleared after successful login

**Severity:** Minor  
**Priority:** Low  

### Preconditions
- User is on the Login page  
- User has previously entered invalid credentials  

### Steps to Reproduce
1. Open the Login page  
2. Enter invalid username and password  
3. Click the **Login** button  
4. Observe the error message  
5. Enter valid username and password  
6. Click the **Login** button  

### Actual Result
- User is successfully logged in  
- Previous error message remains visible  

### Expected Result
- User is successfully logged in  
- Error message should be cleared after successful login  
