## **DASH-0005:** Dashboard testing - Items Quantity

> **Summary:** Verify the item quantities card displays the correct item names and quantities.  <br>

**Preconditions:** There should be at least one available item/product in the inventory.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Click the sales record.     | Verify that the sales record page opens without errors.   |
 |  2 | Enter a valid item name.     | Verify that the system accepts the item name without errors.   |
 |  3 | Enter a valid quantity.     | Verify that the system accepts the quantity without errors.   |
 |  4 | Enter a valid date.     | Verify that the system accepts the date without errors.   |
 |  5 | Click the "Record Sale" button.     | Verify that the system records the sale and updates the item quantities card.   |
 |  6 | Open the dashboard.     | Verify that the dashboard opens without errors.   |
 |  7 | Check the item quantities card.     | Verify that the item quantities card displays the item name and the current quantity.   |

**Post-conditions:**

 - The item quantities card continues to update as new sales data comes in.

