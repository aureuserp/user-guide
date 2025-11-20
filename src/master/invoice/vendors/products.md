# Products

The **Products** module in **AureusERP** (Vendor side) is where users can manage goods and services supplied by vendors. This guide walks you through the steps to create and manage a product offered by a vendor.

## Product Creation

### Steps to Create a Product

1. Navigate to **`Invoices → Vendors → Products`** as shown in the below image.

   ![Create Product](/images1/invoices/vendor_product.png)

2. Fill out the form with the following fields:

   ### Basic Details

   - **_Name:_** Enter the product or service name.
   - **_Description:_** Optional field to add product details.
   - **_Images:_** Upload product images as needed.
   - **_Tags:_**
     > You can **create a new tag** or **select from existing** tags.

   ![Create Product](/images1/invoices/product_general.png)

   ### Settings Section

   - **_Type:_** Choose between:

     - **_Goods:_** Tangible items requiring stock tracking.
     - **_Service:_** Intangible offerings like consulting or maintenance.

   > 🛈 Selecting **Goods** reveals an **Inventory** section at the bottom of the page.

   ### Inventory (Visible if 'Goods' is selected)

   > ![Create Product](/images1/invoices/product_inventory.png)

   - **_Reference:_** Product reference code.
   - **_Barcode:_** Product barcode.
   - **_Category:_**
     - Select an existing category.
     - Or click the ➕ icon to create a new one.
     - By default, **All** is selected.
   - **_Company:_** Choose from the list of companies (multi-company support).

   ![Create Product](/images1/invoices/product_settings.png)

   ### Pricing Section

   - **_Price:_** The price at which you sell the product.
   - **_Cost:_** The cost at which you buy the product from the vendor.
   - **_Product Taxes:_** Applicable taxes when you sell this product.
   - **_Supplier Taxes:_** Applicable taxes charged by the vendor when you purchase the product.

   ![Create Product](/images1/invoices/product_price.png)

3. **Action Buttons**

   - **_Create:_** Save and create the product.
   - **_Create & Create Another:_** Save and reset form for new entry.
   - **_Cancel:_** Exit the form without saving.

## After Product Creation

Upon clicking **Create**, the system redirects to the **View Product** page.

- **_Print Labels:_**
  - Opens a modal with the following fields:
    - **_Number of Labels\*:_** Enter number of labels to print.
    - **_Format:_** Choose label dimension and price inclusion (e.g., 2x7 with price, 4x12 without price).
      ![Create Product](/images1/invoices/product_print.png)
  - Clicking **Submit** downloads a PDF of generated labels.
- **_Delete:_** Permanently removes the product.

![Create Product](/images1/invoices/product_view.png)

## Product Management

From the **View Product** page, you can also:

### Edit Product

Update product details.

### Attributes

- Clicking **Attributes** redirects to the **Manage Attributes** page.
- Click **Add Attribute** to open a modal:
  - **_Attribute\*:_** Select or create a new attribute.
  - **_Values\*:_** Enter the values associated with the selected attribute.
    ![Create Product](/images1/invoices/product_attri.png)
    > 🛈 Once created, **variants** for the selected attributes are generated automatically.

![Create Product](/images1/invoices/product_manage_attri.png)

### Variants Management

Manage product variants with the following actions:

- **_View:_** See variant details.
- **_Edit:_** Update variant info.
- **_Delete:_** Remove specific variant.

![Create Product](/images1/invoices/product_manage_vari.png)

## Summary

This guide covered the steps to create and manage products in the **Vendor** section of **AureusERP**. You learned how to fill out product details, manage inventory for goods, set pricing, and handle product variants through attributes. Efficient product management ensures smooth vendor operations and accurate invoicing.
