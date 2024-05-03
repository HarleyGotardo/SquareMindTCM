## **SALESREC-0002:** Sales record testing - Invalid Item Name

> **Summary:** verifies that an error message is displayed when an invalid item name is entered.  <br>

**Preconditions:** User is logged in and on the sale record page.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter an invalid item name into the item field.     | Verify that System shows error for invalid   |
 |  2 | Enter valid quantity into the quantity field.     | Verify that System accepts without errors.   |
 |  3 | Enter a valid date into the date field.     | Verify that System accepts without errors.   |
 |  3 | Click on the "Record Sale" button.     | Verify that System shows error due to invalid name.   |

**Post-conditions:**

 - Sale is not recorded.
