## **REG-0004:** Registration testing - Invalid Username

> **Summary:** Verify that error message indicating invalid username format.  <br>

**Preconditions:** _None_

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 |  Enter valid email "example@email.com" into the email/number field.    | Verify that the email "example@email.com" is accepted and displayed in the email/number field.   |
 |  2 |  Enter invalid username (contains special characters) into the username field.    | Verify that the system identifies the username as invalid due to the special characters and displays an error message.   |
 |  3 |  Enter valid password "pass123" into the password field.    | Verify that the password "pass123" is accepted and displayed as hidden characters in the password field.   |
 |  3 |  Click on the "Register Account" button.    | Verify that due to the invalid username, the system does not process the registration and maintains the error message.   |

**Post-conditions:**

 - No new account is created.
 - The user remains on the registration page.

