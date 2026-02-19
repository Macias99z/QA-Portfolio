# Test Cases - Krakvet registration

## TC-REG-01 Registration with valid email

Steps: 

1. Open Krakvet registration page
2. Enter valid email address
3. Enter valid password
4. Repeat valid password
5. Agree to read the terms and conditions
6. Submit registration form

Expected result: 
Clear confirmation message informing user that the account has been created successfully

STATUS: FAIL 

Related Bug: KRK-REG-01

## TC-REG-02 Login after registration

Steps:
1. Navigate to login page
2. Enter registered email and password
3. Click Login

Expected Result:
User is logged in successfully nad directed to the main page


Status:

FAIL

Actual result: 

The user is logged in, but the website redirects them to the My Profile window and asks them to fill in the password that has already been entered. There is no need to fill that blank, logged in user can start shopping after going to Main Page by himself.

## TC-REG-04 Re-registration with same email

Steps: 
1. Attempt to register using already registered email

Expected Result: 
Clean error message informing that the email is already in use

Status:
PASS
