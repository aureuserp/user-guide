# Quotation

The **Quotation** module in the **Sales** plugin of **AureusERP** allows users to draft, manage, and convert quotations into sales orders. A quotation serves as a preliminary offer sent to the customer detailing product pricing, terms, and delivery conditions. This guide walks you through creating a quotation, managing its sections, and following its lifecycle.

## Quotation Creation

### Steps to Create a New Quotation

1. Navigate to **Sales >> Orders >> Quotations >> New Quotation** as shown in the below image.

   ![Create Quotation](../../../images/quotation_create_1.png)

2. Filling up fields as per the **section** defeind below :

   ### 🧾 General Section

   - **_Customer:_** Select the customer to whom the quotation is issued.
   - **_Expiration Quotation Date:_** Set the date after which the quotation will no longer be valid.
   - **_Payment Term:_** Define the terms under which the customer must pay (e.g., Net 30, Immediate).

   ![Create Quotation](../../../images/invoice_create_general.png)

   ### Order Line

   Click on **Add Product** to open fields related to product selection.

   - **_Product Variants\*:_** Choose applicable product variant options.
   - **_Quantity\*:_** Enter how many units the customer wants.
   - **_Unit of Measure\*:_** Choose the unit (e.g., Dozen, Units).
   - **_Lead Time:_** Estimated time to fulfill the order.
   - **_Packaging Quantity:_** Number of items per package.
   - **_Packaging Unit:_** Define the packaging type or unit.
   - **_Unit Price\*:_** Price per unit of product.
   - **_Margin:_** Profit margin in absolute value.
   - **_Margin (%):_** Profit margin percentage.
   - **_Taxes:_** Select applicable tax groups.
   - **_Discount (%):_** Discount on the line item.
   - **_Amount:_** Auto-calculated total after applying taxes and discounts.

   ![Create Invoice](../../../images/invoice_create_invoicelines.png)

   ### Optional Products

   - **Product\***: Choose an optional upsell/cross-sell product.
   - **Description\***: Provide a brief description.
   - **Quantity\***: Specify number of units.
   - **Unit of Measure**: Unit like Dozen, Units.
   - **Unit Price\***: Sale price per unit.
   - **Discount (%)**: Any promotional or negotiated discount.

   ![Create Invoice](../../../images/invoice_create_invoicelines.png)

   ### Other Information

   - **Sales Subsection**

     - **Sales Person**: Assign internal user responsible for the sale.
     - **Customer Reference**: Reference number given by the customer.
     - **Tags**: Useful for filtering and classification.

   - **Shipping Subsection**

     - **Delivery Date**: Expected shipment/delivery date.

   - **Tracking Subsection**

     - **Source Document**: Reference to any linked internal document.
     - **Campaign**: Select a marketing campaign.
     - **Medium**: Indicate the communication medium (e.g., Email, Web).
     - **Source**: Source of the lead or order (e.g., AdWords, Facebook).

   - **Additional Information Subsection**

     - **Company**: If you operate in multi-company mode, select the company issuing the quotation.
     - **Currency\***: Choose the currency for the quotation. (Default: USD)

     ![Create Invoice](../../../images/invoice_create_other_1.png)

3. Action Buttons

   At the bottom of the form, you will find:

   - **Create**: Saves and creates the quotation.
   - **Create & Create Another**: Saves current quotation and opens a new quotation form.
   - **Cancel**: Discards the changes and exits the quotation creation screen.

## After Quotation Creation

Click **Create** to save and navigate to the **View Quotation** page.

### Available Actions on View Page:

- **Edit**: Modify quotation details.
- **Confirm**: Turn the quotation into a Sales Order.
- **Cancel**: Mark the quotation as void.
- **Preview**: View a PDF/print-friendly version.
- **Delete**: Permanently remove the quotation.

![Create Quotation](../../../images/invoice_view.png)

> 🛈 At this point, the document is still a draft and not yet a confirmed sale.

## After Confirming Quotation

When you click **Confirm**, the status changes from **Quotation** to **Sales Order**, and you are redirected to the **Edit Order** page.

### What Happens on Confirmation:

- **Triggers Delivery**: For stockable products, a delivery order is generated.
- **Triggers Invoice**: If billing is set to manual or automatic.

![Create Invoice](../../../images/invoice_view.png)

## 🚚 Delivery Management (Optional if Product is Stockable)

- Navigate to the **Delivery** tab.
- **Confirm Picking**: Confirm items to be picked from inventory.
- **Validate Delivery**: Validate that products have been shipped.

> 🛈 Stock is reserved and reduced from inventory automatically.

![Create Invoice](../../../images/invoice_view.png)

## Invoice Generation

- Invoices are created only **after delivery is validated** (if invoice policy is on delivery).

> 🛈 You can generate, send, and register payment directly from the invoice page.

![Create Invoice](../../../images/invoice_view.png)

## Flow Summary

```sh

Quotation (Draft)
    ↓
Confirm Sale
    ↓
Sales Order (Confirmed)
    ↓
Delivery Order (If products require shipping)
    ↓
Create Invoice
    ↓
Send Invoice / Register Payment
    ↓
Sale Completed
```

This is the complete quotation lifecycle in the **Sales** plugin of **AureusERP**, enabling seamless order fulfillment from quote to payment.
