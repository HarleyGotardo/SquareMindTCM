## **REG-0006:** Registration testing - All Fields Empty

> **Summary:** Verify that error messages indicating all fields are required.  <br>

**Preconditions:** _None_

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 |  Leave the email/number field empty.    | Verify that the system identifies the email/number field as required and displays an error message.   |
 |  2 |  Leave the username field empty.    | Verify that the system identifies the username field as required and displays an error message.   |
 |  3 |  Leave the password field empty.    | Verify that the system identifies the password field as required and displays an error message.   |
 |  3 |  Click on the "Register Account" button.    | Verify that due to the empty fields, the system does not process the registration and maintains the error messages.   |

**Post-conditions:**

 - No new account is created.
 - The user remains on the registration page.
