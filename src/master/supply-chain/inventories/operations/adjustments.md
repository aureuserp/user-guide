# Adjustments

Inventory **Adjustments** are used to correct, update, or scrap stock quantities within your warehouse.  
They help maintain accurate inventory levels, handle damaged goods, or adjust quantities during physical stock counts.

**Use Case:**  
Adjustments are essential for keeping your stock records accurate and up to date. They allow users to manually increase, decrease, or remove quantities due to stock discrepancies, losses, or damages.

## Quantities

**Definition:**  
Quantity adjustments let you manually add, update, or correct product quantities in specific warehouse locations.

**Use Case:**  
Used during physical inventory checks or when products are received or misplaced without a formal receipt or delivery record. It helps sync actual stock with the system.

### Steps to Add Quantity

1. Navigate to **`Inventory → Operations → Adjustments → Quantities`** as shown below:

   <ImagePopup src="/images1/inventory/quantities_navigation.png" alt="Quantities Navigation" />

2. Fill in the following fields:

   - **_Location:_** Select the warehouse location where the product quantity needs to be updated (e.g., Stock, Input, Output, or Quality Control).
   - **_Product:_** Choose the product for which the quantity is being adjusted.
   - **_Package:_** Select the package type if the product is stored in a specific packaging (e.g., Box, Pallet, Carton).
   - **_Counted Quantity:_** Enter the actual quantity counted physically at the selected location.
   - **_Scheduled At:_** Specify the date and time when the adjustment should take effect. This helps in planning and scheduling inventory updates.

   <ImagePopup src="/images1/inventory/quantity_adjustment.png" alt="Quantity Adjustment" />

3. **Action Buttons:**

   - **Create:** Save and record the quantity adjustment.
   - **Create & Create Another:** Save and open a new form for additional adjustments.
   - **Cancel:** Exit without saving changes.

## Scraps

**Definition:**  
A **Scrap** represents the removal of damaged, expired, or unusable items from your inventory.  
Scrapping ensures that these products are no longer counted as available stock.

**Use Case:**  
Used when items become broken, defective, expired, or are returned in an unsellable condition. This prevents overreporting of usable stock and maintains accurate inventory valuation.

### Steps to Create a New Scrap

1. Navigate to **`Inventory → Operations → Adjustments → Scraps`** as shown below:

   <ImagePopup src="/images1/inventory/scraps_navigation.png" alt="Scrap Navigation" />

2. Fill in the following details:

   - **_Product:_** Select the product being scrapped from inventory.
   - **_Package:_** Choose the packaging type if applicable (e.g., Carton, Box, Crate).
   - **_Quantity:_** Enter the number of items being scrapped.
   - **_Owner:_** Select the owner of the product, if the warehouse handles multiple ownerships (useful in multi-company setups).
   - **_Unit of Measure:_** Choose the measurement unit for the quantity being scrapped (e.g., Units, Kilograms, Dozens).
   - **_Source Location:_** Specify from where the products are being removed (e.g., Stock, Quality Control, Output).
   - **_Tags:_** Add identifying tags for better tracking or categorization (e.g., Damaged, Expired, Returned).
   - **_Scrap Location:_** Select the scrap location where the scrapped products will be stored (e.g., Scrap Area, Waste Section).
   - **_Source Document:_** Enter or link the document that led to the scrap (e.g., Sales Return, Production Order, or Manual Adjustment).
   - **_Company:_** Choose the company under which this scrap is recorded (in case of multi-company environments).

   <ImagePopup src="/images1/inventory/scrap_creation.png" alt="Scrap Creation" />

3. **Action Buttons:**

   - **Create:** Save and create the scrap record.
   - **Create & Create Another:** Save and open a new blank form.
   - **Cancel:** Discard and go back to the list view.

### Scrap Workflow Actions

After creating a scrap record, you are redirected to the **Scrap View Page**, where you can perform the following actions:

<ImagePopup src="/images1/inventory/scrap_view.png" alt="Scrap View" />

- **View:** Review all scrap details and history.
- **Edit:** Modify scrap details while in draft state.
- **Validate:** Confirm the scrap; the record state changes from **Draft → Done** and the stock is updated automatically.
- **Delete:** Permanently remove the scrap record.
- **Moves:** Check the stock movement record created due to the scrap action.
   <ImagePopup src="/images1/inventory/scrap_moves.png" alt="Scrap Moves" />

## Summary

The **Adjustments** feature in the Inventory module ensures that your warehouse stock remains accurate and up to date. It supports:

- **Quantities:** Add or update product quantities manually across different locations to fix discrepancies.
- **Scraps:** Remove damaged, expired, or unusable items from inventory to maintain clean and accurate stock data.

These operations help in maintaining **inventory integrity**, **accurate reporting**, and **reliable product valuation** across all warehouses.
