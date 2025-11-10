# Product

The **Products** module in the **Purchases** plugin of **AureusERP** allows procurement teams to manage goods and services they procure from vendors. It supports detailed tracking of vendor-specific information such as product pricing, lead times, product codes, and discount structures.

## Product Creation

### Steps to Create a Product

1. Navigate to **`Purchases → Orders → Products → Create Product`**

   ![Create Product](../../../images/create_product.png)

2. Fill out the form with the following fields:

   ### Basic Details

   - **Name:** Enter the product or service name.
   - **Description:** Add optional product details or notes.
   - **Images:** Upload product images as needed.
   - **Tags:** Select from existing tags or create new ones to classify the product.

   ![Create Product](../../../images/create_product_basic.png)

   ### Settings Section

   - **Type:** Choose from the following options:
     - _Goods_
     - _Service_
       > 🛈 Selecting **Goods** reveals the **Inventory** section.

   ### 3. Inventory Section _(Visible if 'Goods' is selected)_

   ![Create Product](../../../images/create_product_inventory.png)

   - **Reference:** Product reference code.
   - **Barcode:** Product barcode.
   - **Category\***:
     - Select from existing product categories or click ➕ to create one.
   - **Company:** Assign the product to a specific company.

   ![Create Product](../../../images/create_product_setting.png)

   ### 4. Pricing Section

   - **Price\***: The retail price of the product.
   - **Cost:** The cost of the product from the vendor.

   ![Create Product](../../../images/create_product_price.png)

3. Action Buttons

   - **Create:** Save and finish product creation.
   - **Create & Create Another:** Save and open a new product form.
   - **Cancel:** Exit without saving.

## After Product Creation

After clicking **Create**, you will be redirected to the **View Product** page.

Here you can manage:

- **Print Labels:**
  - Opens a modal with the following fields:
    - **Number of Labels\***: Enter number of labels to print.
    - **Format**: Choose label dimension and price inclusion (e.g., 2x7 with price, 4x12 without price).
      ![Create Product](../../../images/create_product_label.png)
  - Clicking **Submit** downloads a PDF of generated labels.
- **Delete:** Permanently removes the product.

![Create Product](../../../images/create_product_view.png)

## Product Management

From the **View Product** page, you can also:

### Edit Product

Update product details.

### Attributes

- Clicking **Attributes** redirects to the **Manage Attributes** page.
- Click **Add Attribute** to open a modal:
  - **Attribute\***: Dropdown to select or create new attribute.
  - **Values\***: Enter the values associated with the selected attribute.
    ![Create Product](../../../images/create_product_attribute_1.png)
    > 🛈 Once created, **variants** for the selected attributes are generated automatically.

![Create Product](../../../images/created_product_attribute.png)

### Variants Management

Manage product variants with the following actions:

- **View**: See variant details.
- **Edit**: Update variant info.
- **Delete**: Remove specific variant.

![Create Product](../../../images/created_product_varients.png)

## Manage Vendors for a Product

Click on the Vendors tab from the View Product page to see and manage the vendors who supply this product. This section lets you add vendor details like price, delivery time, and product codes used by the vendor.

> 📌 Purpose: This helps the purchase team keep track of which vendor offers what price, how fast they can deliver, and what name/code they use for the product.

### ➕ Add Vendor Price

Click **Add Vendor** to open a modal form with the following fields:

- **Vendor:** Select a vendor from the registered list.
- **Vendor Product Name:** The name the vendor uses for this product.
- **Vendor Product Code:** Supplier’s product code.
- **Delivery Lead Time (Days):** Estimated days needed by the vendor to deliver.
- **Product\***: Choose the product variant this price applies to.
- **Quantity:** Minimum quantity for which this pricing applies.
- **Unit Price:** Price offered by the vendor.
- **Currency:** Currency of transaction (e.g., USD, INR).
- **Valid From:** Start date for the pricing validity.
- **Valid Until:** Expiry date for the pricing.
- **Discount (%):** Discount offered by the vendor.
- **Company:** Company this vendor pricing is assigned to.

### 💡 Use Case

Procurement teams can maintain vendor-wise price lists, identify cost-effective options, and track delivery lead times — all in one centralized location.

> 📌 **Purpose:** Maintain clarity and control over vendor relationships by tracking variant-specific costs, timelines, and vendor codes directly within the product record.

---

This concludes the **Product Creation** process in the **Purchases Plugin** of **AureusERP**.
