## **SALESREC-0004:** Sales record testing - Invalid Date

> **Summary:** verifies that an error message is displayed when an invalid date is entered.  <br>

**Preconditions:** User is logged in and on the sale record page.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 |  Enter a valid item name into the item field.    | Verify that System accepts without errors.   |
 |  2 |  Enter valid quantity into the quantity field.    | Verify that System accepts without errors.   |
 |  3 |  Enter an invalid date into the date field.    | Verify that System shows error for invalid date.   |
 |  3 |  Click on the "Record Sale" button.    | Verify that System shows error due to invalid date.   |

**Post-conditions:**

 - Sale is not recorded.

