# Configurations

The **Configurations** section in the **Purchases** plugin of **AureusERP** helps administrators define essential data such as vendor pricing, product attributes, packaging, and categories. Proper configuration ensures smooth procurement workflows, accurate pricing, and structured product information.

## Vendor Price Lists

> **Why it's used:** Vendor Price Lists allow businesses to manage and track the pricing agreements made with different suppliers. This ensures that procurement teams can access up-to-date pricing information, apply negotiated rates, and maintain consistency in purchasing processes.

### Steps to Create Vendor Price List

1. Navigate to **`Purchase → Configurations → Vendor Price Lists`** as shown in the image below.

   ![Vendor Price List Navigation](/images1/purchases/vendor_price_list_navigation.png)

2. Clicking on **New Vendor Price List** opens a form with the following sections:

   #### General Section

   - **_Vendor:_** Choose the vendor for this price list.
   - **_Vendor Product Name:_** Name of the product as referred to by the vendor.
   - **_Vendor Product Code:_** Unique code or SKU used by the vendor.
   - **_Delivery Lead Time (Days):_** Expected number of days required to deliver the product.

   #### Price Section

   - **_Product:_** Select the related product from your inventory.
   - **_Quantity:_** Minimum quantity to which this pricing applies.
   - **_Unit Price:_** Price per unit charged by the vendor.
   - **_Currency:_** Select the transaction currency.
   - **_Valid From / Valid Until:_** Set the price validity period.
   - **_Discount (%):_** Optional discount on the listed price.
   - **_Company:_** Choose the company associated with the pricing.

   ![Vendor Price List Form](/images1/purchases/vendor_price_list_form.png)

3. After creating, the system redirects to the **View Price List** page where you can **edit** as needed.

## Product Categories

> **Why it's used:** Product Categories help organize products into logical groups, making it easier for procurement teams to manage and search for items. Categorization also aids in reporting and analysis.

### Steps to Create Product Category

1. Navigate to **`Purchase → Configurations → Products → Categories`** as shown in the image below.

   ![Product Categories Navigation](/images1/purchases/product_categories_navigation.png)

2. Clicking **Create** opens the **Create Category** page:

   - **_Name:_** Define the name of the product category (e.g., Women’s Clothing).
   - **_Parent:_** Optional. Choose a parent category if you're building a nested category structure (e.g., All → Clothing).

   > After creation, you can manage or assign products under this category and make further edits.
   > ![Create Product Category](/images1/purchases/product_category_create.png)

## Product Attributes

> **Why it's used:** Product Attributes define specific characteristics of products, such as size, color, or material. This allows for better product differentiation and helps procurement teams select the right items based on required specifications.

### Steps to Create Product Attribute

1. Navigate to **`Purchase → Configurations → Products → Attribute`** as shown in the image below.

   ![Product Attributes Navigation](/images1/purchases/product_attributes_navigation.png)

2. Attributes define variations of products (like size, color, material).

   #### General Section

   - **_Name:_** Define the attribute name (e.g., Size, Color).
   - **_Type:_** Select from:
     - `Radio`: Displays options as radio buttons.
     - `Select`: Dropdown-based options.
     - `Color`: Shows visual color swatches.

   #### Options Section

   Depending on the type selected:

   - **Radio / Select**

     - **_Name:_** Option name (e.g., Small, Medium, Large).
     - **_Extra Price:_** Optional cost added to the base product price.

   - **Color**
     - **_Name:_** Color label (e.g., Red, Blue).
     - **_Color:_** Choose the color visually.
     - **_Extra Price:_** Optional added price.

![Create Product Attribute](/images1/purchases/product_attribute_create.png)

## Product Packaging

> **Why it's used:** Product Packaging defines how products are bundled or packaged for procurement and inventory management. This helps in standardizing packaging units, improving logistics, and ensuring accurate stock tracking.

### Steps to Create Product Packaging

1. Navigate to **`Purchase → Configurations → Products → Packaging`** as shown in the image below.

   ![Product Packaging Navigation](/images1/purchases/product_packaging_navigation.png)

2. Click **Create Packaging** to open a modal:

   - **_Name:_** Name of the packaging unit.
   - **_Barcode:_** Unique barcode for the packaging.
   - **_Product:_** Link the packaging to a specific product.
   - **_Qty:_** Define how many items are in this package.
   - **_Company:_** Associate the packaging with a specific company.

   ![Create Product Packaging](/images1/purchases/product_packaging_create.png)

   > After clicking **Create**, the packaging unit is saved and can be managed later.

## Summary

These configurations enable better data control and automation within the **Purchases** plugin of AureusERP. Correct setup of attributes, vendor pricing, categories, and packaging ensures accurate procurement, inventory tracking, and product catalog management.
