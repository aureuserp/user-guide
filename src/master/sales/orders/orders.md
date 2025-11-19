# Order

The **Orders** module in the **Sales** plugin of **AureusERP** handles all confirmed sales. An order represents a customer’s approved quotation that initiates delivery, invoicing, and fulfillment processes. This guide walks you through creating and managing a sales order.

## Order Creation

### Steps to Create a New Quotation

1. Navigate to **`Sales → Orders → Orders → New Order`** as shown in the below image.

   ![Create Quotation](../../../images1/sales/order_create_1.png)

> 🛈 A Sales Order is generated after a customer accepts a Quotation. It is in **Confirmed** status and triggers delivery and billing workflows.

2. Filling up fields as per the **section** defeind below :

   ### General Section

   - **_Customer:_** Select the customer to whom the order is issued.
   - **_Expiration Quotation Date:_** Set the deadline for order confirmation or cancellation.
   - **_Payment Term:_** Define how and when the customer will pay.

   ![Create Quotation](../../../images1/sales/invoice_create_general.png)

   ### Order Line

   Click **Add Product** to populate product-level details.

   - **_Product Variants:_** Choose applicable product variant options.
   - **_Quantity:_** Quantity being ordered.
   - **_Unit of Measure:_** Units like Dozen, Units, Boxes.
   - **_Lead Time:_** Estimated delivery/fulfillment time.
   - **_Packaging Quantity:_** How many units per package.
   - **_Packaging Unit:_** Label the packaging type.
   - **_Unit Price:_** Price per unit.
   - **_Margin:_** Profit margin per unit.
   - **_Margin (%):_** Profit percentage.
   - **_Taxes:_** Tax rules applicable.
   - **_Discount (%):_** Discount on the product line.
   - **_Amount:_** Automatically calculated total.

   ![Create Invoice](../../../images1/sales/invoice_create_invoicelines.png)

   ### Optional Products

   - **_Product:_** Add optional products offered.
   - **_Description:_** Short detail for the optional product.
   - **_Quantity:_** Optional product quantity.
   - **_Unit of Measure:_** Measurement unit.
   - **_Unit Price:_** Price for the optional product.
   - **_Discount (%):_** Optional product discount.

   ![Create Invoice](../../../images1/sales/invoice_create_optional.png)

   ### Other Information Section

   - **Sales Subsection**

     - **_Sales Person:_** Assigned user for handling the order.
     - **_Customer Reference:_** External customer order reference.
     - **_Tags:_** Used for filtering or classification.

   - **Shipping Subsection**

     - **_Delivery Date:_** Planned shipment date.

   - **Tracking Subsection**

     - **_Source Document:_** Internal reference link.
     - **_Campaign:_** Marketing campaign involved.
     - **_Medium:_** Source medium (Web, Phone, Email, etc.).
     - **_Source:_** Lead origin (e.g., Facebook, Google Ads).

   - **Additional Information Subsection**

     - **_Company:_** Choose the issuing company.
     - **_Currency:_** Default: USD, can be changed.

     ![Create Invoice](../../../images1/sales/invoice_create_other_1.png)

3. Action Buttons

   - **_Create:_** Saves and creates the quotation.
   - **_Create & Create Another:_** Saves current quotation and opens a new quotation form.
   - **_Cancel:_** Discards the changes and exits the quotation creation screen.

## After Order Creation

After clicking **Create**, you are redirected to the **Edit Sales Order** page.

![Create Quotation](../../../images1/sales/salesorder_view.png)

### Available Actions on View Page:

- **_Preview:_** View a PDF/print-friendly version.

  ![Create Quotation](../../../images1/sales/invoice_view_preview.png)

- **_Send by Email:_** Opens email composer to send the quotation to the customer.

  ![Create Quotation](../../../images1/sales/invoice_view_send_email.png)

- **_Confirm:_** Turn the quotation into a Sales Order.
- **_Cancel:_** Mark the quotation as void.
- **_Delete:_** Permanently remove the quotation.

> 🛈 At this point, the document is still a draft and not yet a confirmed sale.

## After Confirming Quotation

When you click **Confirm**, the status changes from **Quotation** to **Sales Order**, and you are redirected to the **Edit Order** page.

![Create Invoice](../../../images1/sales/order_view.png)

### What Happens on Confirmation:

- **_Triggers Delivery:_** For stockable products, a delivery order is generated.
- **_Create Invoice:_** If the invoice policy is set to "Ordered Quantities", an invoice can be created immediately.
- **_Colomn Updates:_** New columns appear in the order lines:
  - **_Quantity Delivered:_** Shows how many units have been shipped.
  - **_Quantity Invoiced:_** Shows how many units have been invoiced.

![Create Invoice](../../../images1/sales/order_view_confirmed.png)

### Delivery Management (Optional if Product is Stockable)

- Navigate to the **Delivery** tab.

  ![Create Invoice](../../../images1/sales/delivery_tab.png)

- **_Confirm Picking:_** Confirm items to be picked from inventory.
- **_Validate Delivery:_** Validate that products have been shipped.

  ![Create Invoice](../../../images1/sales/delivery_validate.png)

> 🛈 Stock is reserved and reduced from inventory automatically.

### Invoice Generation

- Click **Create Invoice** to generate an invoice.
  - If the invoice policy is `Ordered Quantities`, invoices can be created immediately upon order confirmation.
  - If the invoice policy is `Delivered Quantities`, the invoice can only be created after delivery validation.

![Create Invoice](../../../images1/sales/invoice_create.png)

- Navigate to the **Invoice** tab.

> 🛈 You can generate, send, and register payment directly from the invoice page.

![Create Invoice](../../../images1/sales/invoice_view.png)

## Flow Summary

```sh
Quotation (Draft)
   ↓
Confirm Sale
   ↓
Sales Order (Confirmed)
   ↓
Delivery Order (If shipping required)
   ↓
Create Invoice
   ↓
Send Invoice / Register Payment
   ↓
Sale Completed

```

## Summary

The **Orders** module in the **Sales** plugin of **AureusERP** facilitates efficient management of customer orders from quotation to fulfillment. By following this guide, users can create, confirm, and manage sales orders effectively, ensuring smooth operations in sales processing.
