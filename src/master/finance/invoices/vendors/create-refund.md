# Create a refund

A refund records a credit from a vendor, for example for returned goods or an overpayment. It follows the same layout as a bill, so your books stay consistent.

> **In simple words:** A refund is money or credit a vendor gives back to you.

## Create a refund

1. Go to `Invoices → Vendors → Refunds` and click **New**.

   <ImagePopup src="/images1/invoices/refund_create_1.png" alt="Refunds list with the button to create a new refund" />

2. Fill in the form sections below.

### General

**_Vendor:_** Select the supplier issuing the refund.

**_Bill Date:_** Enter the date on the vendor's refund document.

**_Bill Reference:_** Enter the vendor's credit note number.

**_Accounting Date:_** Enter the date the refund is recognized in the books.

**_Recipient Bank:_** Select the vendor's bank account.

**_Due Date:_** Enter the deadline.

**_Payment Term:_** Select a term such as Net 30 or Immediate.

::: info
When you select a payment term, it sets the **Due Date** for you.
:::

<ImagePopup src="/images1/invoices/refund_create_general.png" alt="General section of the refund form" />

### Invoice lines

Click **Add Product** to add a line. Fill in these fields.

**_Product:_** Select the returned item or credited service.

**_Quantity:_** Enter the number of units.

**_Unit:_** Select the unit of measure.

**_Taxes:_** Add the taxes that apply to the return.

**_Discount Percentage:_** Enter any discount from the original bill.

**_Cost:_** Enter the unit cost from the bill.

**_Subtotal:_** The system calculates this as `(Quantity × Cost - Discount) + Taxes`.

<ImagePopup src="/images1/invoices/refund_create_invoicelines.png" alt="Invoice lines section of the refund form" />

### Other information

Under **Accounting**:

**_Incoterm:_** Select the trade term, for example FOB or CIF.

**_Incoterm Location:_** Enter the location for that term.

Under **Secured**:

**_Payment Method:_** Select how the refund is processed.

**_Auto Post:_** Turn on to post the refund when you create it.

**_Checked:_** Turn on to mark the refund as reviewed or approved.

Under **Additional Information**:

**_Company:_** Select the company that receives the refund.

**_Currency:_** Select the refund currency.

<ImagePopup src="/images1/invoices/bill_create_other1.png" alt="Other information section of the refund form" />

3. Click **Create**, **Create & Create Another** or **Cancel**.

## Actions and statuses

A new refund opens in **Draft** status.

<ImagePopup src="/images1/invoices/refund_view1.png" alt="Draft refund with edit, confirm, cancel and delete buttons" />

In Draft, you can use these buttons:

- **Edit:** change the refund fields.
- **Confirm:** post the refund. Status changes from **Draft** to **Posted**.
- **Cancel:** mark the refund as cancelled.
- **Delete:** remove the refund permanently.

After you confirm, these buttons are available:

- **Pay:** opens the payment window.
- **Reset to Draft:** returns the refund to **Draft**.
- **Delete:** removes the refund.

<ImagePopup src="/images1/invoices/refund_confirm.png" alt="Posted refund with pay and reset to draft buttons" />

The **Pay** window has these fields:

**_Amount:_** Enter the amount received or adjusted.

**_Payment Date:_** Enter the date the refund is expected or received.

**_Partner Bank Account:_** Select the vendor's bank account.

**_Payment Method:_** Select the method.

**_Communication:_** The system fills in the refund number, for example RBILL/2025/05/13.

Click **Submit**. The refund status changes to **Paid**.

<ImagePopup src="/images1/invoices/refund_pay.png" alt="Pay window for a posted refund" />

## See also

- [Create a bill](./create-bill.md)
- [Register a payment](./register-payment.md)
- [Manage vendors](./manage-vendors.md)
