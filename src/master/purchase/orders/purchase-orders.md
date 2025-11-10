# Purchase Orders

The **Purchase Orders** module in the **Purchases** plugin of **AureusERP** allows users to manage confirmed purchase agreements with vendors. A Purchase Order (PO) is typically created by confirming a Request for Quotation (RFQ), and it triggers receipt and billing processes.

## Purchase Order Creation

### Steps to Create a New Purchase Order

1. Navigate to **`Purchase → Orders → Purchase Orders → New Purchase Order`** as shown in the below image.

   ![Create Quotation](../../../images/quotation_create_1.png)

2. Fill in the following sections:

   ### General Section

   - **_Vendor:_** Select the supplier for this order.
   - **_Order Deadline:_** The last date to confirm this order.
   - **_Vendor Reference:_** A reference number provided by the vendor.
   - **_Expected Arrival:_** Expected delivery date for the products.
   - **_Agreement:_** Optional – select a linked Purchase Agreement if available.
   - **_Currency:_** Select the transaction currency.

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

   ### Additional Information Section

   - **_Buyer:_** Internal staff member responsible for this purchase.
   - **_Payment Term:_** Payment agreement terms with the vendor.
   - **_Company:_** Company placing the order (for multi-company setups).
   - **_Source Document:_** Reference to any related document (optional).
   - **_Incoterm:_** International Commercial Term defining delivery terms.
   - **_Incoterm Location:_** Specific location for Incoterm application.

   ### Terms and Conditions

   Add any legal, shipping, or other terms agreed with the vendor.

3. Action Buttons

   At the bottom of the form:

   - **Create** – Save and generate the Purchase Order.
   - **Create & Create Another** – Save and open a new order form.
   - **Cancel** – Exit without saving.

## After PO Creation

After clicking **Create**, you are redirected to the **Edit Purchase Order** page.

### Top-right Action Buttons:

- **Send by Email** – Email the PO to the vendor.
- **Print RFQ** – Download or print a PDF version of the PO.
- **Confirm Order** – Finalize and lock the PO.
- **Cancel** – Cancel the order.
- **Delete** – Permanently remove the order.

## After Confirming Purchase Order

Once you click **Confirm Order**:

- The status changes from **Draft** to **Confirmed**.
- The **Receipt** is automatically generated.
- Edit fields become disabled.
- Top-right buttons now show:
  - **Confirm Receipt Date**
  - **Create Bill**
  - **Unlock**

## Receipt Validation (Stockable Products Only)

1. Click on the **Receipts** tab.
2. Click **Edit** to update actual received quantities.
3. Click **Validate** to confirm delivery.
4. Stock gets reserved and reduced from inventory.

## Vendor Bill Generation

After validating the receipt:

1. Click **Create Bill** – the bill will be **automatically generated** from the PO details.
2. ⚠️ **Note:** If the **receipt is not validated**, you’ll get a **validation error**.
3. Navigate to the **Vendor Bills** tab to review and manage the generated bill.

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
