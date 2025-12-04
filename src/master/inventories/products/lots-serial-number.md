# Lots / Serial Numbers

In the Inventory module, **Lots and Serial Numbers** are unique identifiers used to track product batches or individual items throughout their lifecycle from purchase or production to sale or delivery.  
They enable accurate traceability, quality control, and compliance with regulatory standards.

**Use Case:**

- **Lots** are used for tracking products in batches (e.g., medicines, food, or manufactured goods).
- **Serial Numbers** are used for tracking each unit individually (e.g., electronics, machinery, or luxury goods).

This feature ensures that every product movement can be traced back to its origin, improving transparency and accountability across the supply chain.

## Lots/Serial Number Creation

### Steps to Create a Lot / Serial Number

1. Navigate to **`Inventory → Products → New Lots/Serial Number`** as shown below:

  <ImagePopup src="/images1/inventory/lots_navigation.png" alt="Lots Navigation" />

2. Fill in the following details:

   - **_Name:_** The unique name or code for the lot or serial number.  
     Example: _LOT-001_ (for batch tracking) or _SN-00045_ (for serial tracking).

   - **_Product:_** Select the product to which this lot or serial number belongs.  
     This links the identifier directly to a specific product record.

   - **_Reference:_** Optional field used for adding any external or internal reference, such as a manufacturing order number, purchase order number, or supplier batch code.

   - **_Description:_** Add additional details about the lot or serial number, such as production date, expiration date, or other remarks for internal tracking.

  <ImagePopup src="/images1/inventory/create_lot.png" alt="Create Lot" />

3. **Action Buttons:**

   - **_Create:_** Save the lot or serial number and open its detail page.
   - **_Create & Create Another:_** Save the current record and open a blank form for the next one.
   - **_Cancel:_** Discard the current entry and return to the list view.

## View Page

After creating a record, you are redirected to the **Lot / Serial Number View Page**, where you can manage and monitor all related details.

<ImagePopup src="/images1/inventory/lot_view.png" alt="Lot View" />

### Tabs on the View Page

- **View:** Displays the general details such as name, product, reference, and description.

- **Edit:** Allows you to update or modify the details of the selected lot or serial number.

- **Locations:** Displays the **quantities by location** — showing where this specific lot or serial number currently exists in the warehouse.  
  This view helps you track how much stock from a particular batch is stored at each location.

## Summary

The **Lots / Serial Numbers** feature helps maintain accurate product traceability by allowing tracking at the batch or individual unit level.

- **Batch Tracking (Lots):** Useful for managing groups of products with shared production or expiry details.
- **Unit Tracking (Serial Numbers):** Ideal for products that require individual tracking for warranty or service purposes.
- **Location Insights:** View quantities by warehouse or location for precise stock visibility.

This functionality ensures complete traceability, improves quality assurance, and provides end-to-end visibility into product movements throughout your inventory.
