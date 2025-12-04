# Request for Quotation (RFQ)

In **AureusERP**, a **Request for Quotation (RFQ)** is the first step in the purchase process. It allows the purchasing team to ask suppliers for price quotes before placing an order. This helps companies compare offers and choose the best vendor based on price, delivery time, and other terms.

## RFQ Creation

### Steps to Create a New RFQ

1. Navigate to **`Purchases → Orders → Request For Quotations → New RFQ`** as shown in the below image.

   <ImagePopup src="/images1/purchases/quotation_create_1.png" alt="Create Quotation" />

2. Filling up fields as per the **section** defined below:

   ### General Section

   - **_Vendor:_** Select the vendor (supplier) from whom you want to request a quotation.
   - **_Order Deadline:_** Last date for vendor to respond to this RFQ.
   - **_Vendor Reference:_** Add a reference or order ID from the vendor’s side for cross-verification.
   - **_Expected Arrival:_** Estimated date of delivery.
   - **_Agreement:_** If this RFQ is part of a purchase agreement (e.g., blanket order), link the agreement here.
   - **_Currency:_** The currency to be used in this transaction. This is often auto-filled with your company's default.

   <ImagePopup src="/images1/purchases/rfq_general_section.png" alt="RFQ General Section" />

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

   <ImagePopup src="/images1/purchases/rfq_product_section.png" alt="RFQ Product Section" />

   ### Additional Information Section

   - **_Buyer:_** The internal user (employee) responsible for this purchase.
   - **_Payment Term:_** Terms under which payment will be made, like “30 days,” “Immediate,” etc.
   - **_Company:_** If you're running multiple companies in AureusERP, select the one initiating this purchase.
   - **_Source Document:_** If this RFQ is linked to another document (like a sales order), reference it here.
   - **_Incoterm:_** International commercial term for shipping responsibility (e.g., FOB, CIF).
   - **_Incoterm Location:_** The place tied to the incoterm (e.g., port name or delivery warehouse).

   <ImagePopup src="/images1/purchases/rfq_additional_info.png" alt="RFQ Additional Information" />

   ### Terms and Conditions

   Write any legal terms, warranty clauses, refund conditions, or additional instructions that apply to this order.

3. Action Buttons

   At the bottom of the RFQ form, you’ll see the following buttons:

   - **_Create:_** Saves and creates the RFQ.
   - **_Create & Create Another:_** Saves the current RFQ and resets the form.
   - **_Cancel:_** Discards all unsaved data.

## After RFQ Creation

Once created, you are redirected to the **Edit Purchase Order** view.

<ImagePopup src="/images1/purchases/rfq_bill_edit.png" alt="Create RFQ" />

### Available Actions on View Page:

- **_Edit Quotation:_** Modify RFQ details.
- **_Vendor Bills:_** View vendor bills.
- **_Receipts:_** Manage delivery receipts.
- **_Send by Email:_** Send this RFQ directly to the vendor.
   <ImagePopup src="/images1/purchases/rfq_bill_view.png" alt="Create RFQ" />
- **_Print RFQ:_** Download or print the quote in PDF format.
- **_Confirm Order:_** Approve the RFQ and convert it into a **Purchase Order**.
   <ImagePopup src="/images1/purchases/rfq_bill_view1.png" alt="Create RFQ" />
- **_Cancel:_** Cancel the RFQ.
- **_Delete:_** Permanently delete the RFQ.

## After Confirmation RFQ

Once you **Confirm Order**, the RFQ becomes a **Purchase Order**. At this point:

- The document changes from **RFQ** to **Confirmed Purchase Order**
- Fields are locked for editing
- A **Receipt** is automatically generated
- New buttons appear:

  - **_Confirm Receipt Date:_**
  - **_Create Bills:_**
  - **_Unlock:_** (to make changes again)

<ImagePopup src="/images1/purchases/rfq_bill_confirmed.png" alt="Create RFQ" />

## Receipt Validation Flow

1. Go to the **Receipts** tab.
   <ImagePopup src="/images1/purchases/rfq_receipt_tab.png" alt="Create RFQ" />
2. Click **_Edit_** if needed (e.g., change quantity received).
   <ImagePopup src="/images1/purchases/rfq_receipt_edit.png" alt="Create RFQ" />
3. Click **_Validate_** to confirm that products have been received into inventory.
   <ImagePopup src="/images1/purchases/rfq_receipt_validate.png" alt="Create RFQ" />

> ⚠️ Only after validating the receipt can you proceed to create vendor bills.

## Vendor Bill Generation

1. Click **_Create Bill_**.
   <ImagePopup src="/images1/purchases/rfq_bill_create.png" alt="Create RFQ" />
2. The system auto-fills bill data from the purchase order.
   <ImagePopup src="/images1/purchases/rfq_bill_auto_fill.png" alt="Create RFQ" />
3. You can review, **_edit_**, and save the bill.

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

## Summary

This guide detailed the process of creating and managing a Request for Quotation (RFQ) in **AureusERP**. You learned how to fill out the RFQ form, confirm the order, validate receipts, and generate vendor bills, ensuring a smooth procurement workflow.
