## **REG-0005:** Registration testing - Mismatched Passwords

> **Summary:** Verify that error message indicating mismatched passwords.  <br>

**Preconditions:** _None_

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 |  Enter valid email "example@email.com" into the email/number field.    | Verify that The email "example@email.com" is accepted and displayed in the email/number field.   |
 |  2 |  Enter valid username "user123" into the username field.    | Verify that The username "user123" is accepted and displayed in the username field.   |
 |  3 |  Enter password "pass123" into the password field.    | Verify that The password "pass123" is accepted and displayed as hidden characters in the password field.   |
 |  4 |  Enter different password "pass456" into the confirm password field.   | Verify that The system identifies the mismatch between the password and confirm password fields and displays an error message.   |
 |  5 |  Click on the "Register Account" button.    | Verify that Due to the mismatch in passwords, the system does not process the registration and maintains the error message.   |

**Post-conditions:**

 - No new account is created.
 - The user remains on the registration page.

