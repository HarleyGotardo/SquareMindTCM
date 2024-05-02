## **IM-0004:** Inventory Management testing - Delete Item

> **Summary:** Verify that a product can be successfully deleted from the inventory.  <br>

**Preconditions:** The user is logged into the system and on the inventory management page. There is at least one item in the inventory.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Find the item to delete.     | Verify that the item to be deleted is found and selected.   |
 |  2 | Long press on the item to trigger the delete option.     | Verify that The delete option appears after long pressing the item.   |
 |  3 | Click on the delete option.     | Verify that a confirmation dialog for deletion appears.   |
 |  4 | Confirm the deletion.     | Verify that the item is removed from the inventory and no longer appears in the list.   |

**Post-conditions:**

 - The item is successfully deleted from the inventory.

