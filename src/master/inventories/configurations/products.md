# Products

Products in the Inventory module help you structure, define, and manage all items stored, purchased, and sold through your business operations. This section covers product categories, product attributes, and packaging setup.

## Categories

A category allows you to group and organize products for better management and easier searching. Proper categorization helps ensure fast access to products while performing inventory operations such as stock transfers, product reporting, and item classification.

**Use Case:** Create categories to group similar products together for easier navigation and reporting.

### Steps to Create a Category

1. Navigate to **`Inventory → Configurations → Products → Categories`** as shown below:

   ![Product Categories Navigation](/images1/inventory/categories_navigation.png)

2. Fill in the following fields:

   - **_Name:_** Name of the category (e.g., Electronics, Furniture, Groceries)
   - **_Parent Category (optional):_** Select a parent category if you want to create a sub-category (e.g., Mobile Phones under Electronics)
   - **_Routes:_** Select the default warehouse routes that should apply to all products under this category. Routes control how products move through the warehouse (e.g., receive in multiple steps, cross-dock, pick-pack-ship). If selected, products in this category will follow those inventory flow rules automatically.

   ![Category Routes Selection](/images1/inventory/category_routes_selection.png)

3. Action Buttons

   - **_Create:_** Save the category
   - **_Create & create another:_** Save and open a new entry form
   - **_Cancel:_** Exit without saving

## Attributes

Attributes allow you to define characteristics for your products such as size, color, material, brand, etc. These attributes are used when creating product variants (e.g., a T-shirt that comes in different sizes and colors).

**Use Case:** Create attributes to define product features and enable variants.

### Steps to Create an Attribute

1. Navigate to **`Inventory → Configurations → Products → Attributes`** as shown below:

   ![Product Attributes Navigation](/images1/inventory/attributes_navigation.png)

2. Fill in the following fields:

   - **_Attribute Name:_** Name of the attribute (e.g., Size, Color, Material)
   - **_Display Type:_** How the attribute will be shown (dropdown, color picker, text)
   - **_Values:_** Add the specific values for the attribute (e.g., for Size: Small, Medium, Large; for Color: Red, Blue, Green)

   ![Attribute Values Entry](/images1/inventory/attribute_values_entry.png)

3. Action Buttons

   - **_Create:_** Save the attribute
   - **_Create & create another:_** Save and open a new entry form
   - **_Cancel:_** Exit without saving

## Packaging

Packaging defines how products are grouped, stored, or moved — such as Box of 10 units, Pack of 6 bottles, or Carton of 50 pieces. It helps in managing warehouse logistics, stock counts, sales, and purchase units based on packaging.

**Use Case:** Create packaging to manage how products are packed, stored, and moved in the warehouse.

### Steps to Create Packaging

1. Navigate to **`Inventory → Configurations → Products → Packaging`** as shown below:

   ![Warehouse Management Navigation](/images1/inventory/packaging_navigation.png)

2. Fill in the following fields:

   - **_Name:_** Name for the packaging (e.g., Pack of 6, Box of 12)
   - **_Barcode:_** Barcode for scanning this packaging type during stock movement or sales
   - **_Product:_** Select the product this packaging belongs to (e.g., Soft Drink Bottle for Pack of 6 Bottles)
   - **_Qty:_** Number of units inside the package (e.g., 6 if there are six bottles in one pack)
   - **_Company:_** Select the company this packaging setup is related to (useful for multiple companies)
   - **_Package Type:_** Type of packaging (Box, Bag, Carton, Pallet)
   - **_Routes:_** Select warehouse routes if this packaging follows a specific movement rule (e.g., Dropship, Replenish, Cross-dock)

   ![Packaging Configuration](/images1/inventory/packaging_configuration.png)

3. Action Buttons

   - **_Save:_** Save this packaging configuration
   - **_Create & Create Another:_** Save and open a new entry form
   - **_Cancel:_** Exit without saving

### Summary

In the Inventory module, you can efficiently organize products by creating:

- **Categories:** Group items for better navigation
- **Attributes:** Define product features and variants
- **Packaging:** Specify how products are packed and moved

This structure helps streamline product search, stock management, traceability, and warehouse operations.
