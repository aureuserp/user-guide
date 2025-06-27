# Request for Quotation (RFQ)

In **AureusERP**, a **Request for Quotation (RFQ)** is the first step in the purchase process. It allows the purchasing team to ask suppliers for price quotes before placing an order. This helps companies compare offers and choose the best vendor based on price, delivery time, and other terms.

## RFQ Creation

### Steps to Create a New RFQ

1. Go to **Purchases >> Orders >> Request For Quotations >> New RFQ**as shown in the below image.

   ![Create Quotation](../../../images/quotation_create_1.png)

2. Filling up fields as per the **section** defeind below :

   ### General Section

   - **_Vendor:_** Select the vendor (supplier) from whom you want to request a quotation.
   - **_Order Deadline:_** Last date for vendor to respond to this RFQ.
   - **_Vendor Reference:_** Add a reference or order ID from the vendor’s side for cross-verification.
   - **_Expected Arrival:_** Estimated date of delivery.
   - **_Agreement:_** If this RFQ is part of a purchase agreement (e.g., blanket order), link the agreement here.
   - **_Currency:_** The currency to be used in this transaction. This is often auto-filled with your company's default.

   ![RFQ General Section](../../../images/rfq_general_section.png)

   ### Product Section

   Click on **Add Product** to add items to your quotation request.

   - **_Product:_** Select the product you want to buy from the list of existing products.
   - **_Expected Arrival:_** Specify when you expect to receive the product.
   - **_Quantity:_** How many units of the product you want to order.
   - **_Unit:_** Unit of measure such as Units, Dozens, Kilograms, etc.
   - **_Packaging Qty:_** Number of items in one package or box. Helps in bulk handling.
   - **_Packaging:_** Select the type of packaging (e.g., carton, box, etc.).
   - **_Unit Price:_** Enter the price offered by the vendor.
   - **_Taxes:_** Apply the relevant tax group/rate to this product.
   - **_Discount (%):_** Enter any vendor-provided discount.
   - **_Amount:_** Auto-calculated total for the line item based on quantity, price, taxes, and discount.

   ![RFQ Product Section](../../../images/rfq_product_section.png)

   ### Additional Information Section

   - **_Buyer:_** The internal user (employee) responsible for this purchase.
   - **_Payment Term:_** Terms under which payment will be made, like “30 days,” “Immediate,” etc.
   - **_Company:_** If you're running multiple companies in AureusERP, select the one initiating this purchase.
   - **_Source Document:_** If this RFQ is linked to another document (like a sales order), reference it here.
   - **_Incoterm:_** International commercial term for shipping responsibility (e.g., FOB, CIF).
   - **_Incoterm Location:_** The place tied to the incoterm (e.g., port name or delivery warehouse).

   ### Terms and Conditions

   Write any legal terms, warranty clauses, refund conditions, or additional instructions that apply to this order.

3. Action Buttons

   At the bottom of the RFQ form, you’ll see the following buttons:

   - **Create**: Saves and creates the RFQ.
   - **Create & Create Another**: Saves the current RFQ and resets the form.
   - **Cancel**: Discards all unsaved data.

## After RFQ Creation

Once created, you are redirected to the **Edit Purchase Order** view.

### Available Actions on View Page:

- **Edit Quotation**: Modify RFQ details.
- **Vendor Bills**: View or create vendor bills.
- **Receipts**: Manage delivery receipts.
- **Send by Email**: Send this RFQ directly to the vendor.
- **Print RFQ**: Download or print the quote in PDF format.
- **Confirm Order**: Approve the RFQ and convert it into a **Purchase Order**.
- **Cancel**: Cancel the RFQ.
- **Delete**: Permanently delete the RFQ.

![Create RFQ](../../../images/rfq_bill_view.png)

## After Confirmation RFQ

Once you **Confirm Order**, the RFQ becomes a **Purchase Order**. At this point:

- The document changes from **RFQ** to **Confirmed Purchase Order**
- Fields are locked for editing
- A **Receipt** is automatically generated
- New buttons appear:

  - **Confirm Receipt Date**
  - **Create Bills**
  - **Unlock** (to make changes again)

## Receipt Validation Flow

1. Go to the **Receipts** tab.
2. Click **Edit** if needed (e.g., change quantity received).
3. Click **Validate** to confirm that products have been received into inventory.

> ⚠️ Only after validating the receipt can you proceed to create vendor bills.

## Vendor Bill Generation

1. Click **Create Bill**.
2. The system auto-fills bill data from the purchase order.
3. You can review, edit, and save the bill.
4. Register payment when ready.

## Full RFQ-to-Bill Flow

```sh
RFQ (Draft)
    ↓
Confirm Order
    ↓
Purchase Order (Confirmed)
    ↓
Receipt (Confirmed & Validated)
    ↓
Create Vendor Bill
    ↓
Register Payment
    ↓
Purchase Completed
```
