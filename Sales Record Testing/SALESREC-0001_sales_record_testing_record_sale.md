## **SALESREC-0001:** Sales record testing - Record Sale

> **Summary:** verifies that a sale can be successfully recorded.  <br>

**Preconditions:** User is logged in and on the sale record page.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter valid item name into the item field.     | Verify that system accepts input and no error if item exists.   |
 |  2 | Enter valid quantity into the quantity field.     | Verify that system accepts input and no error if quantity is positive.   |
 |  3 | Enter a valid date into the date field.     | Verify that system accepts input and no error if date is not in future.   |
 |  4 | Click on the "Record Sale" button.     | Verify that sale is recorded, inventory decreases, and success message appears.   |
 

**Post-conditions:**

 - Sale is recorded successfully.
