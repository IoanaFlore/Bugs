# Bugs

Below are some Bugs that I found in website https://automationteststore.com/


--------------------------------------
**Priority and Severity**
P1-High

**Title**
Account can be created only with digits in the First Name

**Description**
A valid account can be created only with digits in the first name

**Steps to Reproduce**
1. Go to https://automationteststore.com/
2. Click on "Login or register " button
3. Press "Continue" button from "I AM A NEW CUSTOMER" section
4. Add only digits at First Name
5. Complete with validate date all fields from register page
6. Check "Privacy Policy" checkbox
7. Click on "Continue" button

**Expected result**
A error message " You introduce an invalid name".

**Actual result**
Account was created with success without error message.

--------------------------------------------------
**Priority and Severity**
P5-Low
**Title**
Button "Login or register" don't have same format like there's buttons.
**Description**
Button "Login or register" from bar menu doesn't have same format, all buttons have caps lock.

**Steps to Reproduce**
1. Go to https://automationteststore.com/
2. View "Login or register " button


**Expected result**
"Login or register" button have same format like the other buttons.

**Actual result**
"Login or register" button don't have same format like the other buttons.

--------------------------------------
**Priority and Severity**
P1-High

**Title**
An user can add as many products as user wants to the cart

**Description**
In cart at "Quantity" section an user can add unlimited products

**Steps to Reproduce**
1. Go to https://automationteststore.com/
2. Click on "CART " button
3. Add at Quantity unlimitted products
4.  Press button "CHECHOUT"


**Expected result**
A error message " You introduce too many products".

**Actual result**
No error message and a user can check order.

