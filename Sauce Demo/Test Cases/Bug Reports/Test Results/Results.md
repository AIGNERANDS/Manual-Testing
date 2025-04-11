# Test Execution Report

**Project:** Sauce Demo  
**Test Objective:** Validate login, add-to-cart, and checkout functionalities.  
**Test Environment:**  
**Browser:** Chrome (latest)  
**OS:** Windows 10 / macOS (update based on what you used)

**URL:** https://www.saucedemo.com

**Tester:** Aigner A.

**Date:** 04/11/2025


## Test Cases Executed
### Test Case ID: TC_Login_001
**Test Scenario:** Verify login with incorrect credentials

**Preconditions:** User is on the login page

**Test Steps:**

Enter invalid username and password.

Click the "Login" button.
Expected Result: An error message should be displayed.
Actual Result: Error message was displayed.
Status: Pass

### Test Case ID: TC_Login_002
Test Scenario: Verify login with correct credentials
Preconditions: User is on the login page
Test Steps:

Enter valid username and password.

Click the "Login" button.
Expected Result: User is redirected to the products page.
Actual Result: User was successfully redirected to the products page.
Status: Pass

### Test Case ID: TC_Cart_001
Test Scenario: Add items to cart
Preconditions: User is logged in
Test Steps:

Select multiple items.

Click "Add to Cart" for each item.
Expected Result: Items are added to the shopping cart.
Actual Result: Items were successfully added to the cart.
Status: Pass

### Test Case ID: TC_Cart_002
Test Scenario: Remove items from the shopping cart
Preconditions:

User is logged in.

Items are already added to the cart.

Test Steps:

Navigate to the shopping cart.

Click "Remove" next to an item.

Expected Result:
The selected item is removed from the cart, and the cart is updated.

Actual Result:
Item was successfully removed from the cart, and the cart updated correctly.

Status: Pass


### Test Case ID: TC_Checkout_001
Test Scenario: Complete checkout process
Preconditions: Items are added to the cart
Test Steps:

Click the cart icon.

Proceed to checkout.

Enter user information.

Complete the purchase.

Expected Result: Checkout is completed successfully.

Actual Result: Checkout was completed successfully.

Status: Pass
