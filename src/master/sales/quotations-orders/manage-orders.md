# Manage orders

An order is a confirmed quotation. The Orders page lists all of them, so you can follow what is delivered, what is invoiced and what is still open. From an order you can create an invoice, lock it, or cancel it.

> **In simple words:** Orders are the quotations your customers said yes to. Use this page to track and invoice them.

## Overview

Open `Sales → Orders → Orders`. Each row shows the **Number**, **Creation Date**, **Customer**, **Sales Person**, **Amount Total** and **Status**.

Use the tabs above the list:

- **_Default:_** All orders.
- **_My Orders:_** Orders where you are the sales person.
- **_To Invoice:_** Orders that are ready to be invoiced.
- **_Up Selling:_** Orders with the **Upselling** invoice status. See [Sell more to the same customer](../invoicing/order-to-upsell.md).
- **_Archived:_** Deleted orders.

Use **Group by**, the search box and the filter button to narrow the list. See [Search, filter and group records](../../getting-started/search-filter-group.md).

<ImagePopup src="/images1/sales/orders_list.png" alt="Orders list with the tabs Default, My Orders, To Invoice, Up Selling and Archived" />

::: info
Most orders start as a quotation. Create one in [Create a quotation](./create-quotation.md) and confirm it. See [Send and confirm a quotation](./send-and-confirm-quotation.md).
:::

## Open an order

Click an order to open it. The state bar shows **Sales Order**. The page has the tabs **View**, **Edit**, **Invoices** and **Deliveries**.

The **Order Line** tab has two extra columns:

- **_Delivered:_** How many units were delivered.
- **_Invoiced:_** How many units were invoiced.

On the edit page these columns are named **Quantity Delivered** and **Quantity Invoiced**.

<ImagePopup src="/images1/sales/order_view_confirmed.png" alt="Confirmed order with Delivered and Invoiced columns on the order lines" />

## Actions and statuses

The buttons at the top of an order are:

- **_Cancel:_** Cancels the order. You can email the customer at the same time.
- **_Create Invoice:_** Opens the **Create Invoice** window.
- **_Preview:_** Shows the document as the customer sees it.
- **_Lock:_** Locks the order. The button then reads **Unlock**.

::: info
**Create Invoice** shows only while the order is waiting to be invoiced.
:::

### Create an invoice

1. Click **Create Invoice**.
2. In the **Create Invoice** window, keep **Regular invoice**.
3. Click **Submit**.

Aureus creates the invoice for the quantities allowed by your invoicing policy. See [Invoicing policies](../invoicing/invoicing-policies.md) and [Create an invoice from an order](../invoicing/order-to-invoice.md).

<ImagePopup src="/images1/sales/create_invoice_window.png" alt="Create Invoice window with the Regular invoice option, Submit and Cancel buttons" />

### Invoices tab

The **Invoices** tab lists the invoices made from this order. The number shows how many there are.

### Deliveries tab

The **Deliveries** tab lists the deliveries of this order. The number shows how many there are.

<ImagePopup src="/images1/sales/delivery_tab.png" alt="Deliveries tab of an order" />

### Lock an order

Click **Lock** to stop changes to a confirmed order. Click **Unlock** to allow changes again.

To lock every order automatically, turn on **Lock Confirm Sales** in `Sales → Settings`. See [Settings](../configuration/settings.md).

## See also

- [Send and confirm a quotation](./send-and-confirm-quotation.md)
- [Create an invoice from an order](../invoicing/order-to-invoice.md)
- [Sell more to the same customer](../invoicing/order-to-upsell.md)
- [Invoicing policies](../invoicing/invoicing-policies.md)
