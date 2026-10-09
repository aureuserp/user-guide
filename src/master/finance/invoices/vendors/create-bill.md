# Create a bill

A bill is the document a vendor sends for goods or services you bought. Recording it lets you track what you owe and plan payments on time.

> **In simple words:** A bill is a record of money you owe a vendor.

## Create a bill

1. Go to `Invoices → Vendors → Bills` and click **New**.

   <ImagePopup src="/images1/invoices/bill_create_1.png" alt="Bills list with the button to create a new bill" />

2. Fill in the form sections below.

### General

**_Vendor:_** Select the supplier who issued the bill.

**_Bill Date:_** Enter the date on the vendor's bill.

**_Bill Reference:_** Enter the vendor's invoice number.

**_Accounting Date:_** Enter the date the bill is recognized in the books.

**_Payment Reference:_** Enter a reference or transaction ID for internal tracking.

**_Recipient Bank:_** Select the vendor's bank account.

**_Due Date:_** Enter the payment deadline.

**_Payment Term:_** Select a term such as Net 30 or Immediate.

::: info
When you select a payment term, it sets the **Due Date** for you.
:::

<ImagePopup src="/images1/invoices/bill_create_general.png" alt="General section of the bill form" />

### Invoice lines

Click **Add Product** to add a line. Fill in these fields.

**_Product:_** Select the item or service you bought.

**_Quantity:_** Enter the number of units.

**_Unit:_** Select the unit of measure, for example Units or Dozens.

**_Taxes:_** Add the vendor-side taxes.

**_Discount Percentage:_** Enter any negotiated discount.

**_Cost:_** Enter the unit price.

**_Subtotal:_** The system calculates this as `(Quantity × Cost - Discount) + Taxes`.

<ImagePopup src="/images1/invoices/vendor_create_invoicelines.png" alt="Invoice lines section of the bill form" />

### Other information

Under **Accounting**:

**_Incoterm:_** Select the trade term, for example FOB or CIF.

**_Incoterm Location:_** Enter the location for that term.

Under **Secured**:

**_Payment Method:_** Select how you will pay, for example wire transfer.

**_Auto Post:_** Turn on to post the bill when you create it.

**_Checked:_** Turn on to mark the bill as reviewed or approved.

Under **Additional Information**:

**_Company:_** Select the company that pays the bill (multi-company setups).

**_Currency:_** Select the bill currency.

<ImagePopup src="/images1/invoices/bill_create_other.png" alt="Other information section of the bill form" />

3. Click **Create**, **Create & Create Another** or **Cancel**.

## Actions and statuses

A new bill opens in **Draft** status.

<ImagePopup src="/images1/invoices/bill_view.png" alt="Draft bill with edit, confirm, cancel and delete buttons" />

In Draft, you can use these buttons:

- **Edit:** change the bill fields.
- **Confirm:** post the bill. Status changes from **Draft** to **Posted**.
- **Cancel:** mark the bill as cancelled.
- **Delete:** remove the bill permanently.

After you confirm, these buttons are available:

- **Pay:** opens the payment window.
- **Reset to Draft:** returns the bill to **Draft**.
- **Credit Note:** creates a credit note. Enter a **Reason** and **Date**.
- **Delete:** removes the bill.

<ImagePopup src="/images1/invoices/bill_confirm.png" alt="Posted bill with pay, reset to draft and credit note buttons" />

The **Pay** window has these fields:

**_Amount:_** Enter the amount to pay.

**_Payment Date:_** Enter the payment date.

**_Partner Bank Account:_** Select the bank account.

**_Payment Method:_** Select the method.

**_Communication:_** The system fills in the bill number, for example BILL/2025/05/13.

Click **Submit**. The bill status changes to **Paid**.

<ImagePopup src="/images1/invoices/bill_pay.png" alt="Pay window for a posted bill" />

## See also

- [Manage vendors](./manage-vendors.md)
- [Register a payment](./register-payment.md)
- [Create a refund](./create-refund.md)
- [Payment terms](../configuration/payment-terms.md)
- [Incoterms](../configuration/incoterms.md)
