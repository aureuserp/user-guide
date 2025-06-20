# Order Creation

The **Orders** module in the **Sales** plugin of **AureusERP** handles all confirmed sales. An order represents a customer’s approved quotation that initiates delivery, invoicing, and fulfillment processes. This guide walks you through creating and managing a sales order.

## Order Creation

### Steps to Create a New Quotation

1. Navigate to **Sales >> Orders >> Orders >> New Order** as shown in the below image.

   ![Create Quotation](../../../images/quotation_create_1.png)

> 🛈 A Sales Order is generated after a customer accepts a Quotation. It is in **Confirmed** status and triggers delivery and billing workflows.

2. Filling up fields as per the **section** defeind below :

   ### 🧾 General Section

   - **_Customer:_** Select the customer to whom the order is issued.
   - **_Expiration Quotation Date\*:_** Set the deadline for order confirmation or cancellation.
   - **_Payment Term:_** Define how and when the customer will pay.

   ### Order Line

   Click **Add Product** to populate product-level details.

   - **_Product Variants\*:_** Choose applicable product variant options.
   - **_Quantity\*:_** Quantity being ordered.
   - **_Unit of Measure\*:_** Units like Dozen, Units, Boxes.
   - **_Lead Time:_** Estimated delivery/fulfillment time.
   - **_Packaging Quantity:_** How many units per package.
   - **_Packaging Unit:_** Label the packaging type.
   - **_Unit Price\*:_** Price per unit.
   - **_Margin:_** Profit margin per unit.
   - **_Margin (%):_** Profit percentage.
   - **_Taxes:_** Tax rules applicable.
   - **_Discount (%):_** Discount on the product line.
   - **_Amount:_** Automatically calculated total.

   ### Optional Products

   - **_Product\*:_** Add optional products offered.
   - **_Description\*:_** Short detail for the optional product.
   - **_Quantity\*:_** Optional product quantity.
   - **_Unit of Measure:_** Measurement unit.
   - **_Unit Price\*:_** Price for the optional product.
   - **_Discount (%):_** Optional product discount.

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
     - **_Currency\*:_** Default: USD, can be changed.

3. Action Buttons

   At the bottom of the form, you will find:

   - **Create:** Saves and creates the quotation.
   - **Create & Create Another**: Saves current quotation and opens a new quotation form.
   - **Cancel**: Discards the changes and exits the quotation creation screen.

## After Order Creation

Click **Create** to save and go to the **View Order** page.

### Available Actions:

- **Edit**: Modify the order details.
- **Cancel**: Cancel the order process.
- **Preview**: View a printable version.
- **Delete**: Permanently remove the order.

> 🛈 At this point, the order is in confirmed state and can’t be edited like quotations unless reset.

## 🚚 Delivery Management

- Navigate to **Delivery** tab.
- **Confirm Picking**: Confirm inventory movement.
- **Validate Delivery**: Confirm product dispatch.

> 🛈 Stock gets reserved and reduced in inventory.

## Invoice Generation

- Invoices can be generated based on delivery completion or manually.
- Navigate to the **Invoice** section and click **Create Invoice**.

> 🛈 Invoices can be emailed or downloaded directly.

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

This guide completes the Sales Order creation process in **AureusERP**, enabling seamless conversion of customer quotations into actionable sales.
