# Purchase Orders

The **Purchase Orders** module in the **Purchases** plugin of **AureusERP** allows users to manage confirmed purchase agreements with vendors. A Purchase Order (PO) is typically created by confirming a Request for Quotation (RFQ), and it triggers receipt and billing processes.

## Purchase Order Creation

### Steps to Create a New Purchase Order

1. Navigate to **`Purchase → Orders → Purchase Orders → New Purchase Order`** as shown in the below image.

   ![Create Quotation](../../../images1/purchases/purchase_create_1.png)

2. Fill in the following sections:

   ### General Section

   - **_Vendor:_** Select the supplier for this order.
   - **_Order Deadline:_** The last date to confirm this order.
   - **_Vendor Reference:_** A reference number provided by the vendor.
   - **_Expected Arrival:_** Expected delivery date for the products.
   - **_Agreement:_** Optional – select a linked Purchase Agreement if available.
   - **_Currency:_** Select the transaction currency.

   ![RFQ General Section](../../../images1/purchases/rfq_general_section.png)

   ### Product Section

   Click on **Add Product** to add item lines.

   - **_Product:_** Choose the product to order.
   - **_Expected Arrival:_** Planned arrival date for that specific product.
   - **_Quantity:_** Enter the number of units.
   - **_Unit:_** Measurement unit (e.g., Dozens, Units).
   - **_Packaging Qty:_** Quantity per package.
   - **_Packaging:_** Select packaging type.
   - **_Unit Price:_** Purchase price per unit.
   - **_Taxes:_** Select applicable tax group.
   - **_Discount (%):_** Optional discount on that line item.
   - **_Amount:_** Auto-calculated field based on quantity and unit price.

   ![RFQ Product Section](../../../images1/purchases/rfq_product_section.png)

   ### Additional Information Section

   - **_Buyer:_** Internal staff member responsible for this purchase.
   - **_Payment Term:_** Payment agreement terms with the vendor.
   - **_Company:_** Company placing the order (for multi-company setups).
   - **_Source Document:_** Reference to any related document (optional).
   - **_Incoterm:_** International Commercial Term defining delivery terms.
   - **_Incoterm Location:_** Specific location for Incoterm application.

   ![RFQ Additional Information](../../../images1/purchases/rfq_additional_info.png)

   ### Terms and Conditions

   Add any legal, shipping, or other terms agreed with the vendor.

3. Action Buttons

   At the bottom of the form:

   - **_Create:_** Save and generate the Purchase Order.
   - **_Create & Create Another:_** Save and open a new order form.
   - **_Cancel:_** Exit without saving.

## After PO Creation

After clicking **Create**, you are redirected to the **Edit Purchase Order** page.

![Create RFQ](../../../images1/purchases/po_bill_edit.png)

### Top-right Action Buttons:

- **_Send by Email:_** Email the PO to the vendor.
- **_Print RFQ:_** Download or print a PDF version of the PO.
- **_Confirm Order:_** Finalize and lock the PO.
- **_Cancel:_** Cancel the order.
- **_Delete:_** Permanently remove the order.

## After Confirming Purchase Order

Once you click **Confirm Order**:

- The status changes from **Draft** to **Confirmed**.
- The **Receipt** is automatically generated.
- Edit fields become disabled.
- Top-right buttons now show:
  - **_Confirm Receipt Date:_**
  - **_Create Bill:_**
  - **_Unlock:_**

![Create RFQ](../../../images1/purchases/po_bill_confirmed.png)

## Receipt Validation (Stockable Products Only)

1. Click on the **_Receipts_** tab.
   ![Create RFQ](../../../images1/purchases/rfq_receipt_tab.png)
2. Click **_Edit_** to update actual received quantities.
   ![Create RFQ](../../../images1/purchases/rfq_receipt_edit.png)
3. Click **_Validate_** to confirm delivery.
4. Stock gets reserved and reduced from inventory.
   ![Create RFQ](../../../images1/purchases/rfq_receipt_validate.png)

## Vendor Bill Generation

After validating the receipt:

1. Click **_Create Bill_** – the bill will be **automatically generated** from the PO details.
   ![Create RFQ](../../../images1/purchases/rfq_bill_create.png)
2. Navigate to the **_Vendor Bills_** tab to review and manage the generated bill.
   ![Create RFQ](../../../images1/purchases/rfq_bill_auto_fill.png)
   > ⚠️ **Note:** If the **receipt is not validated**, you’ll get a **validation error**.

## Purchase Order Lifecycle Flow

```sh
Purchase Order (Draft)
   ↓
Confirm Order
   ↓
Receipt (If stockable)
   ↓
Validate Receipt
   ↓
Create Bill
   ↓
Vendor Bill
   ↓
Register Payment
```

## Summary

This guide detailed the process of creating and managing Purchase Orders in the **Purchases** module of **AureusERP**. You learned how to fill out order details, add products, confirm orders, validate receipts, and generate vendor bills. Proper management of purchase orders ensures efficient procurement and accurate financial tracking.
