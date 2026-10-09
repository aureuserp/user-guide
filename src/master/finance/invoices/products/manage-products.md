# Manage products

A product is any good or service you sell on invoices or buy on bills. It stores the price, cost, taxes, category and variants, so each document picks them up automatically.

> **In simple words:** Create the product once, and every invoice and bill can use it.

## Settings

The **Unit of Measure** option in `Invoices → Settings → Manage Products` decides whether you can choose a unit (for example pieces or dozens) on each line. See [Invoice settings](../configuration/settings.md).

## Create a product

1. Go to `Invoices → Customers → Products` or `Invoices → Vendors → Products`. Both menus open the same product list.

   <ImagePopup src="/images1/invoices/product.png" alt="Products list reached from the Customers menu" />
   <ImagePopup src="/images1/invoices/vendor_product.png" alt="Products list reached from the Vendors menu" />

2. Click **New Product** and fill in the form.

### Basic details

- **_Name:_** Enter the product or service name.
- **_Description:_** Add optional product details.
- **_Images:_** Upload product images.
- **_Tags:_** Pick existing tags or create a new one.

<ImagePopup src="/images1/invoices/product_general.png" alt="Basic details section of the product form" />

### Settings

- **_Type:_** Choose **Goods** for tangible items that need stock tracking. Choose **Service** for intangible work such as consulting or maintenance.

::: info
Choosing **Goods** shows the **Inventory** section at the bottom of the form.
:::

<ImagePopup src="/images1/invoices/product_settings.png" alt="Type selection in the product Settings section" />

### Inventory

This section appears only when **Type** is **Goods**.

- **_Reference:_** Enter the product reference code.
- **_Barcode:_** Enter the product barcode.
- **_Category:_** Select a category. **All** is the default. Click the plus icon to create one. See [Product categories](../configuration/product-categories.md).
- **_Company:_** Select the company that owns the product.

<ImagePopup src="/images1/invoices/product_inventory.png" alt="Inventory section of the product form" />

### Pricing

- **_Price:_** Enter the price at which you sell the product.
- **_Cost:_** Enter the price at which you buy it from the vendor.
- **_Product Taxes:_** Select the taxes that apply when you sell the product.
- **_Supplier Taxes:_** Select the taxes the vendor charges when you buy the product.

<ImagePopup src="/images1/invoices/product_price.png" alt="Pricing section with price, cost and tax fields" />

3. Click **Create**.

## Actions and statuses

On the create form:

- **Create:** Saves the product and opens its view page.
- **Create & Create Another:** Saves the product and clears the form.
- **Cancel:** Leaves the form without saving.

On the view page:

- **Edit:** Updates the product details.
- **Print Labels:** Opens a modal. Enter **Number of Labels** and choose a **Format**, such as 2x7 with price or 4x12 without price. Click **Submit** to download a PDF.
- **Delete:** Removes the product permanently.

<ImagePopup src="/images1/invoices/product_view.png" alt="Product view page with Print Labels and Delete buttons" />
<ImagePopup src="/images1/invoices/product_print.png" alt="Print Labels modal with number of labels and format" />

## Add attributes and variants

1. Open the product and click **Attributes**. The **Manage Attributes** page opens.
2. Click **Add Attribute**.
3. Select an **Attribute**, or create a new one.
4. Enter the **Values** for that attribute.
5. Save the modal.

<ImagePopup src="/images1/invoices/product_attri.png" alt="Add Attribute modal with attribute and values" />
<ImagePopup src="/images1/invoices/product_manage_attri.png" alt="Manage Attributes page of a product" />

The app generates the variants for the chosen attributes automatically.

### Manage variants

Each variant has three actions:

- **View:** Shows the variant details.
- **Edit:** Updates the variant.
- **Delete:** Removes the variant.

<ImagePopup src="/images1/invoices/product_manage_vari.png" alt="Variants list with view, edit and delete actions" />

::: tip
Set up attributes first in [Product attributes](../configuration/product-attributes.md) so they are ready to pick.
:::

## See also

- [Invoice settings](../configuration/settings.md)
- [Taxes](../configuration/taxes.md)
- [Create an invoice](../customers/create-invoice.md)
- [Create a bill](../vendors/create-bill.md)
