#  Test Cases – Login Functionality

This document contains **manual test cases** for the Login functionality.  
The test cases demonstrate **QA thinking at Junior / Junior+ level**.

---

## TC-01: Login with valid credentials

**Type:** Positive  
**Priority:** High  
**Severity:** Critical  

### Preconditions
- User is on the Login page
- A valid user account exists in the system

### Steps
1. Open the Login page  
2. Enter a valid username  
3. Enter a valid password  
4. Click the **Login** button  

### Expected Result
- User is successfully logged in  
- User is redirected to the main/dashboard page  

---

## TC-02: Login using Enter key with valid credentials

**Type:** Positive  
**Priority:** Medium  
**Severity:** Major  

### Preconditions
- User is on the Login page
- A valid user account exists in the system

### Steps
1. Open the Login page  
2. Enter a valid username  
3. Enter a valid password  
4. Press the **Enter** key  

### Expected Result
- User is successfully logged in  
- User is redirected to the main/dashboard page  

---

## TC-03: Login with invalid password

**Type:** Negative  
**Priority:** High  
**Severity:** Major  

### Preconditions
- User is on the Login page
- A valid username exists in the system

### Steps
1. Open the Login page  
2. Enter a valid username  
3. Enter an invalid password  
4. Click the **Login** button  

### Expected Result
- User is not logged in  
- Error message about invalid credentials is displayed  
- User remains on the Login page  

---

## TC-04: Login with empty password

**Type:** Negative  
**Priority:** High  
**Severity:** Major  

### Preconditions
- User is on the Login page
- A valid username exists in the system

### Steps
1. Open the Login page  
2. Enter a valid username  
3. Leave the password field empty  
4. Click the **Login** button  

### Expected Result
- User is not logged in  
- Validation or error message is displayed  
- User remains on the Login page  

---

## TC-05: Login with empty username and password

**Type:** Negative  
**Priority:** Medium  
**Severity:** Major  

### Preconditions
- User is on the Login page

### Steps
1. Open the Login page  
2. Leave the username field empty  
3. Leave the password field empty  
4. Click the **Login** button  

### Expected Result
- User is not logged in  
- Validation messages are displayed  
- User remains on the Login page  

---

## ✅ Summary
These test cases cover:
- Positive and negative scenarios
- Field validation
- Login business logic
- Basic UX expectations

  
  
