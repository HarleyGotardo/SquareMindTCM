## **REG-0003:** Registration testing - Invalid Email

> **Summary:** Verify that error message indicating invalid email format.  <br>

**Preconditions:** _None_

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter invalid email "example.com" into the email/number field.     | Verify that the system identifies "example.com" as an invalid email and displays an error message.   |
 |  2 | Enter valid username "user123" into the username field.     | Verify that the username "user123" is accepted and displayed in the username field.   |
 |  3 | Enter valid password "pass123" into the password field.     | Verify that the password "pass123" is accepted and displayed as hidden characters in the password field.   |
 |  3 | Click on the "Register Account" button.     | Verify that due to the invalid email, the system does not process the registration and maintains the error message.   |

**Post-conditions:**

 - No new account is created.
 - The user remains on the registration page.
