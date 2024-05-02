## **IM-0001:** Inventory Management testing - Search

> **Summary:** Verify that the search functionality in the Inventory Management system works as expected.  <br>

**Preconditions:** The user is logged into the system and on the inventory management page. There is at least one item in the inventory.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter a keyword into the search bar.     | Verify that the system displayed a list of items matching the search keyword.   |
 |  2 | Click on the search button.     | Verify that the item was displayed indicating results found.   |

**Post-conditions:**

 - Item displayed on the screen.


Scenario 2

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter a keyword into the search bar.     | Verify that the item is not matching the search keyword was not be displayed.   |
 |  2 | Click on the search button.     | Verify that the item was not displayed indicating no results found.   |

**Post-conditions:**

 - A meesage displayed indicating no item found.
