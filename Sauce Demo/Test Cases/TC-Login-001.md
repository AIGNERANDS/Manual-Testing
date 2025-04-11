## Test Case: Unsuccessful Login with Incorrect Username
**Test Case ID:** TC-Login-001

**Title:** Verify user cannot log in with an invalid username

**Preconditions:**

User is on the Sauce Demo login page.

**Test Steps:**

Entered an invalid username (e.g., debasic_debugger) into the Username field.

Entered a valid password (e.g., secret_sauce) into the Password field.

Click the Login button.

**Test Data:**

**Username:** debasic_debugger  **Password:** secret_sauce

**Expected Result:**

User remains on the login page.

An error message is displayed: "Epic sadface: Username and password do not match any user in this service."

**Priority:**
High

**Labels/Tags:**
Positive Test, Login
