## **SALESREC-0003:** Sales record testing - Invalid Quantity

> **Summary:** verifies that an error message is displayed when an invalid quantity is entered.  <br>

**Preconditions:** User is logged in and on the sale record page.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter a valid item name into the item field.     | Verify that system accepts without errors.   |
 |  2 | Enter an invalid quantity into the quantity field.     | Verify that system shows error for invalid quantity.   |
 |  3 | Enter a valid date into the date field.    | Verify that system accepts without errors.   |
 |  4 | Click on the "Record Sale" button.    | Verify that system shows error due to invalid quantity.   |

**Post-conditions:**

 - Sale is not recorded.
