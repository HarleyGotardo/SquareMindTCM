## **LOGIN-0007:** Login testing - Incorrect Password Case Sensitivity

> **Summary:** Verify that error message indicating invalid password.  <br>

**Preconditions:** The user must have an account with the application.


Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter a valid username into the username field.     | Verify that username is entered successfully   |
 |  2 | Enter the password with incorrect case into the password field.     | Verify that password is entered with incorrect case   |
 |  3 | Click the login button.     | Verify that system displays an error message indicating invalid password   |

**Post-conditions:**

 - The user remains on the login page.

