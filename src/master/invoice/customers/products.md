# Products

The **Products** module in **AureusERP** is where users can manage their goods and services. This guide walks you through the steps to create and manage a product effectively.

## Product Creation

### Steps to Create a Product

1. Navigate to **`Invoices → Customers → Products`** as shown in the below image.

  <ImagePopup src="/images1/invoices/product.png" alt="Create Product" />

2. Fill out the form with the following fields:

   #### Basic Details

   - **_Name:_** Enter the product or service name.
   - **_Description:_** Optional field to add product details.
   - **_Images:_** Upload product images as needed.
   - **_Tags:_** You can **create a new tag** or **select from existing** tags in the dropdown.

  <ImagePopup src="/images1/invoices/product_general.png" alt="Create Product" />

   #### Settings

   - **_Type:_** Choose between:

     - **Goods**
     - **Service** (radio buttons)

   > 🛈 Selecting **Goods** reveals an **Inventory** section at the bottom of the page.

   #### Inventory (Visible if 'Goods' is selected)

  <ImagePopup src="/images1/invoices/product_inventory.png" alt="Create Product" />

   - **_Reference:_** Product reference code.
   - **_Barcode:_** Product barcode.
   - **_Category:_**
     - Select an existing category.
     - Or click the ➕ icon to create a new one.
     - By default, **All** is selected.
   - **_Company:_** Choose from the list of companies (multi-company support).

  <ImagePopup src="/images1/invoices/product_settings.png" alt="Create Product" />

   #### Pricing

   - **_Price:_** Selling price of the product.
   - **_Cost:_** Internal cost price.

  <ImagePopup src="/images1/invoices/product_price.png" alt="Create Product" />

3. **Action Buttons:**
   - **_Create:_** Save and create the product.
   - **_Create & Create Another:_** Save and reset form for new entry.
   - **_Cancel:_** Exit the form without saving.

## After Product Creation

Upon clicking **Create**, the system redirects to the **View Product** page.

- **Print Labels:**
  - Opens a modal with the following fields:
    - **_Number of Labels:_** Enter number of labels to print.
    - **_Format:_** Choose label dimension and price inclusion (e.g., 2x7 with price, 4x12 without price).
      <ImagePopup src="/images1/invoices/product_print.png" alt="Create Product" />
  - Clicking **Submit** downloads a PDF of generated labels.
- **Delete:** Permanently removes the product.

<ImagePopup src="/images1/invoices/product_view.png" alt="Create Product" />

## Product Management

From the **View Product** page, you can also:

### Edit Product

Update product details.

### Attributes

- Clicking **Attributes** redirects to the **Manage Attributes** page.
- Click **Add Attribute** to open a modal:
  - **_Attribute:_** Dropdown to select or create new attribute.
  - **_Values:_** Enter the values associated with the selected attribute.
    <ImagePopup src="/images1/invoices/product_attri.png" alt="Create Product" />
    > 🛈 Once created, **variants** for the selected attributes are generated automatically.

<ImagePopup src="/images1/invoices/product_manage_attri.png" alt="Create Product" />

### Variants Management

Manage product variants with the following actions:

- **View:** See variant details.
- **Edit:** Update variant info.
- **Delete:** Remove specific variant.

<ImagePopup src="/images1/invoices/product_manage_vari.png" alt="Create Product" />

## Summary

The **Products** module in **AureusERP** allows users to efficiently create and manage products or services. By following the steps outlined in this guide, users can add new products, configure their settings, manage attributes and variants, and print labels as needed. This comprehensive approach ensures that businesses can maintain accurate product information and streamline their invoicing processes.
