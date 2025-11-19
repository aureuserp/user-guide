# Packages

In the Inventory module, **Packages** represent grouped or bundled items that are packed together for easier handling, shipping, or storage. A package can contain one or more products, and each package is linked with a specific location, type, and packaging date.

**Use Case:** Packages help track goods that are packed together during inbound (receiving), outbound (delivery), or internal transfer operations. They improve traceability by connecting products with their physical packaging units (e.g., boxes, pallets, or containers).

## Package Creation

### Steps to Create a Package

1. Navigate to **`Inventory → Products → Packages`** as shown below.

   ![Packages Navigation](../../../images1/inventory/packages_navigation.png)

2. Fill in the following details:

   - **_Name:_** The unique name or identifier of the package (e.g., Box-001, Pallet-A12).  
     Helps easily recognize the package during transfers or shipping.

   - **_Package Type:_** Select the predefined type of packaging such as Box, Crate, Pallet, or Carton.  
     The package type determines the dimensions, weight limits, and packaging material.

   - **_Location:_** Choose the current warehouse location where this package is stored (e.g., Stock, Input, Output, Quality Control).  
     This ensures that the system knows exactly where the package is physically placed.

   - **_Pack Date:_** The date on which the package was created or packed.  
     Useful for tracking the packaging timeline and ensuring accurate logistics documentation.

   ![Create Package](../../../images1/inventory/create_package.png)

3. **Action Buttons:**

   - **_Create:_** Save the package and go to its detail page.
   - **_Create & Create Another:_** Save the current package and open a new blank form to create another.
   - **_Cancel:_** Discard the current entry and return to the package list.

## Package View Page

After creating a package, you are redirected to the **Package View Page**, where you can manage and monitor the package details and operations.

![Package View](../../../images1/inventory/package_view.png)

### Tabs on the Package View Page

- **View:** Displays the package details such as name, type, location, and packaging date.

- **Edit:** Allows modification of package details if changes are required.

- **Products:** Shows all the **products contained in the package** along with their respective **quantities**.  
  This helps in verifying what items are inside each package.

- **Manage Operations:** Displays all related **inventory operations** (e.g., deliveries, receipts, transfers) linked with the package.  
  You can track the flow of goods and understand how the package was used across operations.

## Summary

The **Packages** feature provides an organized way to handle grouped products during various inventory operations.

- **Purpose:** Simplifies the management of packed goods for storage and shipment.
- **Traceability:** Connects products with their physical packaging for better tracking.
- **Efficiency:** Enables quick identification of package contents and their operational movements.

This functionality ensures that all products within a package are traceable from packing to delivery, improving warehouse organization and operational visibility.
