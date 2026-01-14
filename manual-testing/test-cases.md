###  Test Cases – Login Functionality

This document contains manual test cases for the Login functionality.  
The test cases are written to demonstrate QA thinking, validation logic, and understanding of positive and negative scenarios at Trainee / Junior level.

---

###  TC-01: Login with valid credentials

**Type:** Positive  
**Priority:** High  
**Severity:** Critical  

**Preconditions:**
- User is on the Login page  
- A valid user account exists in the system  

**Steps:**
1. Open the Login page  
2. Enter a valid username  
3. Enter a valid password  
4. Click the **Login** button  

**Expected Result:**
- User is successfully logged in  
- User is redirected to the post-login page  
- User dashboard or success message is displayed  

---

###  TC-02: Login using Enter key with valid credentials

**Type:** Positive  
**Priority:** Medium  
**Severity:** Major  

**Preconditions:**
- User is on the Login page  
- A valid user account exists in the system  

**Steps:**
1. Open the Login page  
2. Enter a valid username  
3. Enter a valid password  
4. Press the **Enter** key  

**Expected Result:**
- User is successfully logged in  
- User is redirected to the post-login page  

---

###  TC-03: Login with invalid password

**Type:** Negative  
**Priority:** High  
**Severity:** Major  

**Preconditions:**
- User is on the Login page  
- A valid username exists in the system  

**Steps:**
1. Open the Login page  
2. Enter a valid username  
3. Enter an invalid password  
4. Click the **Login** button  

**Expected Result:**
- User is not logged in  
- Error message indicating invalid credentials is displayed  
- User remains on the Login page  

---

###  TC-04: Login with empty password

**Type:** Negative  
**Priority:** High  
**Severity:** Major  

**Preconditions:**
- User is on the Login page  
- A valid username exists in the system  

**Steps:**
1. Open the Login page  
2. Enter a valid username  
3. Leave the password field empty  
4. Click the **Login** button  

**Expected Result:**
- User is not logged in  
- Validation or error message is displayed  
- User remains on the Login page  

---

###  TC-05: Login with empty username

**Type:** Negative  
**Priority:** Medium  
**Severity:** Major  

**Preconditions:**
- User is on the Login page  

**Steps:**
1. Open the Login page  
2. Leave the username field empty  
3. Enter a valid password  
4. Click the **Login** button  

**Expected Result:**
- User is not logged in  
- Validation or error message is displayed  
- User remains on the Login page  

---

###  Automation Coverage

- **TC-01:** Login with valid credentials – Automated  
- **TC-03:** Login with invalid password – Automated  
- **TC-02, TC-04, TC-05:** Covered by manual testing  
