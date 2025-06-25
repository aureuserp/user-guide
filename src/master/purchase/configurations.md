# Configurations 

The **Configurations** section in the **Purchases** plugin of **AureusERP** helps administrators define essential data such as vendor pricing, product attributes, packaging, and categories. Proper configuration ensures smooth procurement workflows, accurate pricing, and structured product information.

## Vendor Price Lists

### Navigation

**Purchase → Configurations → Vendor Price Lists**

### ➕ Create Vendor Price List

Clicking on **New Vendor Price List** opens a form with the following sections:

#### General Section

- **Vendor\***: Choose the vendor for this price list.
- **Vendor Product Name**: Name of the product as referred to by the vendor.
- **Vendor Product Code**: Unique code or SKU used by the vendor.
- **Delivery Lead Time (Days)**: Expected number of days required to deliver the product.

#### Price Section

- **Product**: Select the related product from your inventory.
- **Quantity**: Minimum quantity to which this pricing applies.
- **Unit Price**: Price per unit charged by the vendor.
- **Currency**: Select the transaction currency.
- **Valid From / Valid Until**: Set the price validity period.
- **Discount (%)**: Optional discount on the listed price.
- **Company**: Choose the company associated with the pricing.

After creating, the system redirects to the **View Price List** page where you can **edit** as needed.

## Product Categories

### Navigation

**Purchase → Configurations → Products → Categories**

### ➕ Create Product Category

Clicking **Create** opens the **Create Category** page:

- **Name**: Define the name of the product category (e.g., Women’s Clothing).
- **Parent**: Optional. Choose a parent category if you're building a nested category structure (e.g., All → Clothing).

> After creation, you can manage or assign products under this category and make further edits.

## Product Attributes

### Navigation

**Purchase → Configurations → Products → Attribute**

Attributes define variations of products (like size, color, material).

### ➕ Create Attribute

#### General Section

- **Name**: Define the attribute name (e.g., Size, Color).
- **Type**: Select from:
  - `Radio`: Displays options as radio buttons.
  - `Select`: Dropdown-based options.
  - `Color`: Shows visual color swatches.

#### Options Section

Depending on the type selected:

- **Radio / Select**

  - **Name**: Option name (e.g., Small, Medium, Large).
  - **Extra Price**: Optional cost added to the base product price.

- **Color**
  - **Name**: Color label (e.g., Red, Blue).
  - **Color**: Choose the color visually.
  - **Extra Price**: Optional added price.

## Product Packaging

### Navigation

**Purchase → Configurations → Products → Packaging**

Click **Create Packaging** to open a modal:

- **Name**: Name of the packaging unit.
- **Barcode**: Unique barcode for the packaging.
- **Product**: Link the packaging to a specific product.
- **Qty**: Define how many items are in this package.
- **Company**: Associate the packaging with a specific company.

> After clicking **Create**, the packaging unit is saved and can be managed later.

## ✅ Summary

These configurations enable better data control and automation within the **Purchases** plugin of AureusERP. Correct setup of attributes, vendor pricing, categories, and packaging ensures accurate procurement, inventory tracking, and product catalog management.
