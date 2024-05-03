## **REG-0002:** Registration testing - Valid Credentials (Phone Number)

> **Summary:** Verify that User successfully registers with a phone number.  <br>

**Preconditions:** _None_

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter valid phone number "1234567890" into the email/number field.     | Verify that the phone number "1234567890" is accepted and displayed in the email/number field.   |
 |  2 | Enter valid username "user456" into the username field.     | Verify that the username "user456" is accepted and displayed in the username field.   |
 |  3 | Enter valid password "password789" into the password field.    | Verify that the password "password789" is accepted and displayed as hidden characters in the password field.   |
 |  4 | Click on the "Register Account" button.    | Verify that the system processes the registration and displays a success message indicating that the account has been successfully registered.   |

**Post-conditions:**

 - A new account is created in the system with the provided phone number, username, and password.
 - The user is logged in to the newly created account.

