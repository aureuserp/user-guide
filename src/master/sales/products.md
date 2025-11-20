# Products

The **Products** module in the **Sales** plugin of **AureusERP** enables users to create, manage, and configure goods and services offered for sale. This guide covers everything from product setup to attribute and variant management.

## Product Creation

### Steps to Create a Product

1. Navigate to **`Sales → Products → Create Product`** as shown below:

   ![Create Product](/images1/sales/product_create.png)

2. Fill out the form with the following fields:

   #### Basic Details

   - **_Name:_** Enter the product or service name.
   - **_Description:_** Optional field to add product details.
   - **_Images:_** Upload one or more product images.
   - **_Tags:_** You can **create a new tag** or **select from existing** tags for quick filtering or classification.

   ![Create Product](/images1/invoices/product_general.png)

   #### Settings Section

   - **_Type:_** Choose between:

     - **Goods:** Tangible items requiring stock tracking.
     - **Service:** Intangible offerings like consulting or maintenance.

   > 🛈 Selecting **Goods** reveals an **Inventory** section at the bottom of the page.

   #### Inventory (Visible if 'Goods' is selected)

   ![Create Product](/images1/invoices/product_inventory.png)

   - **_Reference:_** Product reference code.
   - **_Barcode:_** Barcode used for scanning or POS systems.
   - **_Category:_**
     - Select an existing category.
     - Or click the ➕ icon to create a new one.
     - By default, **All** is selected.
   - **_Company:_** Choose from the list of companies (multi-company support).

   ![Create Product](/images1/invoices/product_settings.png)

   #### Pricing Section

   - **_Price:_** The price at which you sell the product.
   - **_Cost:_** The cost at which you buy the product from the vendor.

   ![Create Product](/images1/invoices/product_price.png)

3. Action Buttons

   - **_Create:_** Save and create the product.
   - **_Create & Create Another:_** Save and reset form for new entry.
   - **_Cancel:_** Exit the form without saving.

## After Product Creation

Upon clicking **Create**, the system redirects to the **View Product** page.

- **Print Labels:**
  - Opens a modal with the following fields:
    - **_Number of Labels:_** Enter number of labels to print.
    - **_Format:_** Choose label dimension and price inclusion (e.g., 2x7 with price, 4x12 without price).
      ![Create Product](/images1/invoices/product_print.png)
  - Clicking **Submit** downloads a PDF of generated labels.
- **Delete:** Permanently removes the product.

![Create Product](/images1/invoices/product_view.png)

## Product Management

From the **View Product** page, you can also:

### Edit Product

- Modify product information like name, price, category, or type.
- Useful for making pricing updates or correcting details.

### Attributes

- Clicking **Attributes** redirects to the **Manage Attributes** page.
- Click **Add Attribute** to open a modal:
  - **_Attribute:_** Select or create a new attribute.
  - **_Values:_** Enter the values associated with the selected attribute.
    ![Create Product](/images1/invoices/product_attri.png)
    > 🛈 Once created, **variants** for the selected attributes are generated automatically.

![Create Product](/images1/invoices/product_manage_attri.png)

### Variants Management

Use this section to manage product variants generated via attributes:

- **View:** See variant details.
- **Edit:** Update variant info.
- **Delete:** Remove specific variant.

![Create Product](/images1/invoices/product_manage_vari.png)

## Summary

The **Products** module in **AureusERP** provides a robust framework for managing goods and services. From creation to variant management, users can efficiently handle product data, ensuring accurate inventory and pricing strategies. Explore the features to optimize your sales operations effectively.
