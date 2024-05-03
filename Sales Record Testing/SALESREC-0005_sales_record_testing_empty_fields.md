## **SALESREC-0005:** Sales record testing - Empty Fields

> **Summary:** verifies that an error message is displayed when required fields are left empty.  <br>

**Preconditions:** User is logged in and on the sale record page.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 |  Leave one or more fields (item name, quantity, date) empty.    | Verify that nothing happens   |
 |  2 |  Click on the "Record Sale" button.    | Verify that an error message is displayed indicating that required fields are empty.   |

**Post-conditions:**

 - Sale is not recorded.

