# Products

In the Inventory module, products represent the physical or tangible items that are stocked, stored, moved, and tracked within your warehouses. This page explains how to create products and configure inventory-related settings such as tracking, routes, and quantities.

**Use Case:** Products help manage stock levels, traceability, and movement across warehouses. Enable inventory tracking to monitor quantities, lots, or serial numbers for accurate, real-time control.

## Product Creation

### Steps to Create a Product

1. Navigate to **`Inventory → Products → Products`** as shown below:

  <ImagePopup src="/images1/inventory/products_navigation.png" alt="Products Navigation" />

2. Fill in the following fields:

   - **_Product Name:_** The name of the product (e.g., Laptop, Office Chair, Coffee Beans)
   - **_Description:_** Optional field to add product details.
   - **_Images:_** Upload product images as needed.
   - **_Tags:_**
     > You can **create a new tag** or **select from existing** tags in the dropdown.

  <ImagePopup src="/images1/inventory/product_general.png" alt="Create Product" />

   ### Settings Section

   - **Reference:** Product reference code.
   - **Barcode:** Product barcode.
   - **_Category_**:
     - Select an existing category.
     - Or click the ➕ icon to create a new one.
     - By default, **All** is selected.
   - **Company:** Choose from the list of companies (multi-company support).
   - **Type:** Choose between:
     - **Goods**
     - **Service** _(radio buttons)_

   > 🛈 Selecting **Goods** reveals an **Inventory** section at the bottom of the page.

  <ImagePopup src="/images1/inventory/product_settings.png" alt="Create Product" />

   ### Inventory (Visible if 'Goods' is selected)

   This section defines how the product is tracked and moved within warehouses.

   #### Tracking

   - **_Tracking:_** Enable to start tracking inventory for the product. When enabled, additional tracking options appear.
   - **_Track By:_** Choose how inventory should be tracked:
     - By Quantity: Track only the total number of items in stock
     - By Lots: Track items in batches (useful for manufacturing, food, or pharmaceuticals)
     - By Unique Serial Number: Track each product unit individually using serial numbers

   #### Operation Routes

   - **_Operations Routes:_** Routes determine how the product moves through your supply chain such as how it’s received, processed, and delivered.

     The available routes are automatically generated based on your warehouse shipment configurations.
     For example:

     - Primary Warehouse: Receive in 3 Steps (Input + Quality + Stock)
     - Primary Warehouse: Deliver in 3 Steps (Pick + Pack + Ship)

   These routes ensure each product follows a consistent and well-defined operational path from supplier to customer.
  <ImagePopup src="/images1/inventory/product_routes.png" alt="Create Product" />

   #### Logistics

   - **_Responsible:_** Select the user responsible for managing this product (e.g., Warehouse Manager, Inventory Controller).
   - **_Weight:_** The product’s weight, used for calculating shipment loads or delivery costs.
   - **_Volume:_** The total space occupied by the product (used for warehouse space management).
   - **_Customer Lead Time (Days):_** The number of days needed to deliver the product to the customer after order confirmation.
    <ImagePopup src="/images1/inventory/product_logistics.png" alt="Create Product" />

   ### Pricing Section

   - **Price**: Selling price of the product.
   - **Cost:** Internal cost price.

  <ImagePopup src="/images1/inventory/product_price.png" alt="Create Product" />

3. Action Buttons

   - **_Create:_** Save and create the product record
   - **_Create & Create Another:_** Save and open a new blank form to create another product
   - **_Cancel:_** Exit without saving changes

## Product View Page

After creating a product, you are redirected to the Product View Page where you can manage attributes, variants, and inventory levels.

<ImagePopup src="/images1/inventory/product_view.png" alt="Create Product" />

### Tabs on the Product View Page

- **Edit:** Modify product details or inventory settings
- **Attributes:** Define product attributes (color, size, material) used for creating variants
- **Variants:** Manage multiple versions of the product based on attribute combinations (e.g., T-Shirt – Size M, Color Blue)
- **Quantities**
  The Quantities section helps you manage the physical stock levels of your products across different warehouses or locations.
  ### Steps to Add a New Quantity
  1. Click **Add Quantity** on the Quantities tab
    <ImagePopup src="/images1/inventory/product_add_quantity.png" alt="Create Product" />
  2. Fill the modal fields:
     - **_Location:_** Select the warehouse location where the product is stored (e.g., Stock, Input, Output, Quality Control)
     - **_Package:_** Choose the package type (e.g., Box, Pallet, Carton) if applicable
     - **_On Hand Quantity:_** Enter the number of units physically available at that location
  3. Click **Create** to save the quantity record
    <ImagePopup src="/images1/inventory/product_quantity_modal.png" alt="Create Product" />
- **IN/OUT:**
  The product’s IN/OUT section tracks all incoming and outgoing quantities:
  - **IN:** Stock received through purchase orders or internal transfers
  - **OUT:** Stock delivered or consumed through sales or internal movement

<ImagePopup src="/images1/inventory/product_inout.png" alt="Create Product" />

## Summary

The Products feature in the Inventory module ensures control and traceability over your stock by enabling:

- **Inventory Tracking:** Monitor products by quantity, lot, or serial number
- **Routes:** Define automatic product movement across operations
- **Quantities:** Maintain accurate on-hand stock records for each location
- **Variants & Attributes:** Manage multiple configurations of a single product efficiently

This structure allows for precise stock management, streamlined operations, and transparent traceability across all warehouse activities.
