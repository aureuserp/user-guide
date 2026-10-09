# Create a quotation

A quotation is the offer you send to a customer. It lists the products, quantities, prices and taxes, and the date until which the offer is valid. Create one for every customer request, then send it and confirm it when the customer accepts.

> **In simple words:** A quotation is a draft order that you can still change before the customer agrees.

## Overview

Open `Sales → Orders → Quotations`. The list shows the **Number**, **Creation Date**, **Customer**, **Sales Person**, **Amount Total** and **Status** of each quotation. A summary row shows the total amount.

Use the tabs above the list to switch the view:

- **_Default:_** All quotations and orders.
- **_My Quotations:_** Quotations where you are the sales person.
- **_Quotations:_** Records that are still quotations.
- **_Sales Orders:_** Records that are confirmed orders.
- **_Archived:_** Deleted records.

Above the list you also find **Group by**, a search box and a filter button. See [Search, filter and group records](../../getting-started/search-filter-group.md).

## Create a quotation

1. Go to `Sales → Orders → Quotations`.
2. Click **New Quotation**.

<ImagePopup src="/images1/sales/quotation_create_1.png" alt="Quotations list with the Orders menu, Quotations page and New Quotation button marked" />

The state bar at the top shows **Quotation**, **Quotation Sent** and **Sales Order**. A new record starts as **Quotation**.

### General

- **_Customer:_** Choose the customer. Click the plus icon to create a new one. Required.
- **_Expiration:_** The date until which the offer is valid. Required. The default comes from [Settings](../configuration/settings.md).
- **_Quotation Date:_** The date of the quotation. Required.
- **_Payment Term:_** When the customer pays, for example **Immediate Payment**. Required.

### Order Line

This tab lists the products you offer.

1. Click **Add Product**.
2. Fill in the line:

   - **_Product:_** Choose the product. Required.
   - **_Quantity:_** How many units the customer wants. Required.
   - **_UOM:_** The unit of measure, for example **Units**. Required.
   - **_Packaging Quantity:_** The number of packages.
   - **_Packaging:_** The type of package.
   - **_Unit Price:_** The price of one unit. It is filled in from the product. Required.
   - **_Taxes:_** The taxes that apply to the line.
   - **_Amount:_** The line total. It is calculated for you.

3. Repeat for each product.

Below the lines, Aureus shows **Untaxed Amount** and **Amount Total**.

<ImagePopup src="/images1/sales/quotation_order_line.png" alt="Create Quotation page, Order Line tab with one product line filled in and the totals below" />

::: info
Some columns depend on [Settings](../configuration/settings.md). **Discount** and **Margin** columns appear only when you turn on Discount and Margins. **UOM** and the packaging columns appear only when you turn on Unit of Measure and Packagings. See [Discounts and margins](../products-prices/discounts-margins.md) and [Packagings](../configuration/packagings.md).
:::

### Optional Products

List extra products you suggest to the customer. See [Optional products](./optional-products.md).

### Other Information

- **Sales**

  - **_Sales Person:_** The user who handles this sale.
  - **_Customer Reference:_** The reference number your customer uses.
  - **_Tags:_** Labels to find the quotation later. See [Tags](../configuration/tags.md).

- **Shipping**

  - **_Warehouse:_** The warehouse that ships the goods. It appears when the Inventory plugin is installed.
  - **_Delivery Date:_** The date you promise to deliver.

- **Tracking**

  - **_Source Document:_** A reference to the document this quotation comes from.
  - **_Campaign:_** The marketing campaign behind the sale.
  - **_Medium:_** The channel, for example email.
  - **_Source:_** Where the lead came from.

- **Additional Information**

  - **_Company:_** The company that issues the quotation.

<ImagePopup src="/images1/sales/invoice_create_other_1.png" alt="Other Information tab with Sales, Shipping, Tracking and Additional Information sections" />

### Terms & Conditions

Write the **Note** that applies to this quotation, such as terms of delivery.

### Save the quotation

- Click **Create** to save and open the quotation.
- Click **Create & create another** to save and start a new one.
- Click **Cancel** to leave without saving.

## Actions and statuses

A saved quotation has the status **Quotation**. Send it, then confirm it. See [Send and confirm a quotation](./send-and-confirm-quotation.md).

::: tip
Open **Chatter** on a quotation to write notes or plan an activity. See [Chatter](../../getting-started/chatter.md) and [Activities](../../getting-started/activities.md).
:::

## See also

- [Optional products](./optional-products.md)
- [Send and confirm a quotation](./send-and-confirm-quotation.md)
- [Manage customers](./manage-customers.md)
- [Product prices](../products-prices/index.md)
