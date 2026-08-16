# Bug Report

- **Date:** July 27, 2026

- **Platform:** uTest  

- **Cycle ID:** #55XXXX  

- **App Type:** web application (Browser: Chrome on computer)  

- **Description:**   Favorites - Changing the size of a favorited product creates a duplicate favorite item. 

- **Steps to Reproduce:**  
  1. Go to https://www.ae.com/us/en
  2. Log in with a valid account.
  3. Search for "Tank Top".
  4. Open any tank top product.
  5. Add the product to Favorites.
  6. Open another color or size variant of the same product and add it to Favorites.
  7. Navigate to the Favorites page.
  8. Click the Size selector (e.g., Size: S) for one of the favorited items.
  9. Change the size to another available size (e.g., XS).

- **Expected Result:** The selected favorite item should update to the newly selected size while keeping the same number of favorite items.

- **Actual Result:** Instead of updating the existing favorite item, a new duplicate favorite item is added to the Favorites list, increasing the total number of favorite products.

- **Severity:** Medium  

- **Evidence:**  

  - Screenshot: https://www.image2url.com/r2/default/images/1786909935866-4aa23682-38e4-4075-abeb-4b74fcb9f4ef.png 
  - Screen recording: not uploaded for privacy reasons

- **Status:** Accepted (verified by customer) 
