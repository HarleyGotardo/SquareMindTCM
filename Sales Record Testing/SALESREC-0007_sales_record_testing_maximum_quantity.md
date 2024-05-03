## **SALESREC-0007:** Sales record testing - Maximum Quantity

> **Summary:** verifies that a sale can be recorded with the maximum allowed quantity.  <br>

**Preconditions:** User is logged in and on the sale record page.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter a valid item name into the item field.     | Verify that System accepts without errors.   |
 |  2 | Enter the maximum allowed quantity into the quantity field.     | Verify that System accepts without errors.   |
 |  3 | Enter a valid date into the date field.    | Verify that System accepts without errors.   |
 |  4 | Click on the "Record Sale" button.    | Verify that System records sale without errors.   |

**Post-conditions:**

 - Sale is recorded successfully.

