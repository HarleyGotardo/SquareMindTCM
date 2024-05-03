## **SALESREC-0006:** Sales record testing - Negative Quantity

> **Summary:** verifies that an error message is displayed when a negative quantity is entered.  <br>

**Preconditions:** User is logged in and on the sale record page.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter a valid item name into the item field.     | Verify that system accepts without errors.   |
 |  2 | Enter a negative quantity into the quantity field.     | Verify that system shows error for negative quantity.   |
 |  3 | Enter a valid date into the date field.     | Verify that system accepts without errors.   |
 |  3 | Click on the "Record Sale" button.     | Verify that system shows error due to negative quantity.
   |

**Post-conditions:**

 - Sale is not recorded.

