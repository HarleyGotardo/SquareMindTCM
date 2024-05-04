## **DASH-0003:** Dashboard testing - Total Sales Month

> **Summary:** Verify the total sales by month card displays the correct date and total sales.  <br>

**Preconditions:** There should be at least one available item/product in the inventory.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Click the sales record.     | Verify that the sales record page opens without errors.   |
 |  2 | Enter a valid item name.    | Verify that the system accepts the item name without errors.   |
 |  3 | Enter a valid quantity.     | Verify that the system accepts the quantity without errors.   |
 |  4 | Enter a valid date.     | Verify that the system accepts the date without errors.   |
 |  5 | Click the "Record Sale" button.     | Verify that the system records the sale and updates the total sales card.   |
 |  6 | Check the total sales by month card on the dashboard.     | Verify that the card displays the date in 'yyy/mmm' format and the total sales for that month   |

**Post-conditions:**

 - The card continues to update as new monthly sales data comes in.

