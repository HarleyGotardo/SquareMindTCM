# Test Cases

## Valid Input Test Case

### Steps:
1. Enter valid email "example@email.com" into the email/number field.
2. Enter valid username "user123" into the username field.
3. Enter valid password "pass123" into the password field.
4. Click on the "Register Account" button.

### Expected Behavior:
1. The email "example@email.com" should be successfully entered into the email/number field.
2. The username "user123" should be successfully entered into the username field.
3. The password "pass123" should be successfully entered into the password field.
4. After clicking on the "Register Account" button, the system should process the registration, and a success message should be displayed indicating that the account has been successfully registered.

## Valid Input Test Case (Phone Number)

### Steps:
1. Enter valid phone number "1234567890" into the email/number field.
2. Enter valid username "user456" into the username field.
3. Enter valid password "password789" into the password field.
4. Click on the "Register Account" button.

### Expected Behavior:
Steps and Expected Behavior similar to the Valid Input Test Case.

## Invalid Email Test Case

### Steps:
1. Enter invalid email "example.com" into the email/number field.
2. Enter valid username "user123" into the username field.
3. Enter valid password "pass123" into the password field.
4. Click on the "Register Account" button.

### Expected Behavior:
After clicking on the "Register Account" button, the system should detect the invalid email format and display an error message indicating that the email format is invalid.

## Invalid Username Test Case

### Steps:
1. Enter valid email "example@email.com" into the email/number field.
2. Enter invalid username (contains special characters) into the username field.
3. Enter valid password "pass123" into the password field.
4. Click on the "Register Account" button.

### Expected Behavior:
After clicking on the "Register Account" button, the system should detect the invalid username format (contains special characters) and display an error message indicating that the username format is invalid.

## Mismatched Passwords Test Case

### Steps:
1. Enter valid email "example@email.com" into the email/number field.
2. Enter valid username "user123" into the username field.
3. Enter password "pass123" into the password field.
4. Enter different password "pass456" into the confirm password field.
5. Click on the "Register Account" button.

### Expected Behavior:
After clicking on the "Register Account" button, the system should detect that the passwords entered do not match and display an error message indicating that the passwords do not match.

## Existing Email Test Case

### Steps:
1. Enter existing email "existing@email.com" into the email/number field.
2. Enter valid username "user123" into the username field.
3. Enter valid password "pass123" into the password field.
4. Click on the "Register Account" button.

### Expected Behavior:
After clicking on the "Register Account" button, the system should detect that the email already exists in the database and display an error message indicating that the email already exists.

## Existing Username Test Case

### Steps:
1. Enter valid email "new@email.com" into the email/number field.
2. Enter existing username "existinguser" into the username field.
3. Enter valid password "pass123" into the password field.
4. Click on the "Register Account" button.

### Expected Behavior:
After clicking on the "Register Account" button, the system should detect that the username already exists in the database and display an error message indicating that the username already exists.

## All Fields Empty Test Case

### Steps:
1. Leave the email/number field empty.
2. Leave the username field empty.
3. Leave the password field empty.
4. Click on the "Register Account" button.

### Expected Behavior:
After clicking on the "Register Account" button, the system should detect that all fields are empty and display error messages indicating that all fields are required.

# Post-conditions

## Valid Input Test Case
- A new account is created in the system with the provided email, username, and password.
- The user is logged in to the newly created account.

## Valid Input Test Case (Phone Number)
- A new account is created in the system with the provided phone number, username, and password.
- The user is logged in to the newly created account.

## Invalid Email Test Case
- No new account is created.
- The user remains on the registration page.

## Invalid Username Test Case
- No new account is created.
- The user remains on the registration page.

## Mismatched Passwords Test Case
- No new account is created.
- The user remains on the registration page.

## Existing Email Test Case
- No new account is created.
- The user remains on the registration page.

## Existing Username Test Case
- No new account is created.
- The user remains on the registration page.

## All Fields Empty Test Case
- No new account is created.
- The user remains on the registration page.