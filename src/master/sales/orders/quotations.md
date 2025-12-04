# Quotation

The **Quotation** module in the **Sales** plugin of **AureusERP** allows users to draft, manage, and convert quotations into sales orders. A quotation serves as a preliminary offer sent to the customer detailing product pricing, terms, and delivery conditions. This guide walks you through creating a quotation, managing its sections, and following its lifecycle.

## Quotation Creation

### Steps to Create a New Quotation

1. Navigate to **`Sales → Orders → Quotations → New Quotation`** as shown in the below image.

  <ImagePopup src="/images1/sales/quotation_create_1.png" alt="Create Quotation" />

2. Filling up fields as per the **section** defeind below :

   ### General Section

   - **_Customer:_** Select the customer to whom the quotation is issued.
   - **_Expiration Quotation Date:_** Set the date after which the quotation will no longer be valid.
   - **_Payment Term:_** Define the terms under which the customer must pay (e.g., Net 30, Immediate).

  <ImagePopup src="/images1/sales/invoice_create_general.png" alt="Create Quotation" />

   ### Order Line

   Click on **Add Product** to open fields related to product selection.

   - **_Product:_** Choose applicable product variant options.
   - **_Quantity:_** Enter how many units the customer wants.
   - **_Unit of Measure:_** Choose the unit (e.g., Dozen, Units).
   - **_Lead Time:_** Estimated time to fulfill the order.
   - **_Packaging Quantity:_** Number of items per package.
   - **_Packaging Unit:_** Define the packaging type or unit.
   - **_Unit Price:_** Price per unit of product.
   - **_Margin:_** Profit margin in absolute value.
   - **_Margin (%):_** Profit margin percentage.
   - **_Taxes:_** Select applicable tax groups.
   - **_Discount (%):_** Discount on the line item.
   - **_Amount:_** Auto-calculated total after applying taxes and discounts.

  <ImagePopup src="/images1/sales/invoice_create_invoicelines.png" alt="Create Invoice" />

   ### Optional Products

   - **_Product:_** Choose an optional upsell/cross-sell product.
   - **_Description:_** Provide a brief description.
   - **_Quantity:_** Specify number of units.
   - **_Unit of Measure:_** Unit like Dozen, Units.
   - **_Unit Price:_** Sale price per unit.
   - **_Discount (%):_** Any promotional or negotiated discount.

  <ImagePopup src="/images1/sales/invoice_create_optional.png" alt="Create Invoice" />

   ### Other Information

   - **Sales Subsection**

     - **_Sales Person:_** Assign internal user responsible for the sale.
     - **_Customer Reference:_** Reference number given by the customer.
     - **_Tags:_** Useful for filtering and classification.

   - **Shipping Subsection**

     - **_Delivery Date:_** Expected shipment/delivery date.

   - **Tracking Subsection**

     - **_Source Document:_** Reference to any linked internal document.
     - **_Campaign:_** Select a marketing campaign.
     - **_Medium:_** Indicate the communication medium (e.g., Email, Web).
     - **_Source:_** Source of the lead or order (e.g., AdWords, Facebook).

   - **Additional Information Subsection**

     - **_Company:_** If you operate in multi-company mode, select the company issuing the quotation.
     - **_Currency:_** Choose the currency for the quotation. (Default: USD)

    <ImagePopup src="/images1/sales/invoice_create_other_1.png" alt="Create Invoice" />

3. Action Buttons

   At the bottom of the form, you will find:

   - **_Create:_** Saves and creates the quotation.
   - **_Create & Create Another:_** Saves current quotation and opens a new quotation form.
   - **_Cancel:_** Discards the changes and exits the quotation creation screen.

## After Quotation Creation

Click **Create** to save and navigate to the **Edit Quotation** page.

<ImagePopup src="/images1/sales/salesorder_view.png" alt="Create Quotation" />

### Available Actions on View Page:

- **_Preview:_** View a PDF/print-friendly version.

  <ImagePopup src="/images1/sales/invoice_view_preview.png" alt="Create Quotation" />

- **_Send by Email:_** Opens email composer to send the quotation to the customer.

  <ImagePopup src="/images1/sales/invoice_view_send_email.png" alt="Create Quotation" />

- **_Confirm:_** Turn the quotation into a Sales Order.
- **_Cancel:_** Mark the quotation as void.
- **_Delete:_** Permanently remove the quotation.

> 🛈 At this point, the document is still a draft and not yet a confirmed sale.

## After Confirming Quotation

When you click **Confirm**, the status changes from **Quotation** to **Sales Order**, and you are redirected to the **Edit Order** page.

<ImagePopup src="/images1/sales/order_view.png" alt="Create Invoice" />

### What Happens on Confirmation:

- **_Triggers Delivery:_** For stockable products, a delivery order is generated.
- **_Create Invoice:_** If the invoice policy is set to "Ordered Quantities", an invoice can be created immediately.
- **_Colomn Updates:_** New columns appear in the order lines:
  - **_Quantity Delivered:_** Shows how many units have been shipped.
  - **_Quantity Invoiced:_** Shows how many units have been invoiced.

<ImagePopup src="/images1/sales/order_view_confirmed.png" alt="Create Invoice" />

### Delivery Management (Optional if Product is Stockable)

- Navigate to the **Delivery** tab.

  <ImagePopup src="/images1/sales/delivery_tab.png" alt="Create Invoice" />

- **_Confirm Picking:_** Confirm items to be picked from inventory.
- **_Validate Delivery:_** Validate that products have been shipped.

  <ImagePopup src="/images1/sales/delivery_validate.png" alt="Create Invoice" />

> 🛈 Stock is reserved and reduced from inventory automatically.

### Invoice Generation

- Click **Create Invoice** to generate an invoice.
  - If the invoice policy is `Ordered Quantities`, invoices can be created immediately upon order confirmation.
  - If the invoice policy is `Delivered Quantities`, the invoice can only be created after delivery validation.

<ImagePopup src="/images1/sales/invoice_create.png" alt="Create Invoice" />

- Navigate to the **Invoice** tab.

> 🛈 You can generate, send, and register payment directly from the invoice page.

<ImagePopup src="/images1/sales/invoice_view.png" alt="Create Invoice" />

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

## Summary

This guide completes the Quotation creation process in **AureusERP**, enabling seamless conversion of customer quotations into actionable sales.
