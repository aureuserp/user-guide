# Register a payment

A vendor payment records money you send to a vendor, or money you receive back from one. It keeps your payment history accurate and settles open bills.

> **In simple words:** A payment is the record that you paid a vendor, matched to their bill.

## Create a payment

1. Go to `Invoices → Vendors → Payments` and click **New**.

   <ImagePopup src="/images1/invoices/vendor_payment_create_1.png" alt="Vendor payments list with the button to create a new payment" />

2. Fill in the form fields below.

**_Payment Type:_** Choose **Send** or **Receive**.

- **_Send:_** Record money paid to a vendor, for example a bill settlement.
- **_Receive:_** Record a refund or payment returned by a vendor.

**_Vendor:_** Select the vendor.

**_Amount:_** Enter the total amount sent or received.

**_Vendor Bank Account:_** Select the vendor's bank account.

**_Payment Method:_** Select how you pay, for example Bank, Cash or Cheque.

**_Date:_** Enter the transaction date.

**_Memo:_** Add optional notes or an internal reference.

<ImagePopup src="/images1/invoices/vendor_payment_create_form.png" alt="Vendor payment form with type, vendor, amount and method fields" />

3. Click **Create**.

## Actions and statuses

The payment opens in **Draft** status.

<ImagePopup src="/images1/invoices/vendor_payment_create_view.png" alt="Draft vendor payment with edit, delete, confirm and cancel buttons" />

These buttons are available on the payment:

- **Edit:** change the payment. Only available in **Draft**.
- **Delete:** remove the payment before you confirm it.
- **Confirm:** move the payment to **In Process** and start settlement.
- **Cancel:** cancel the payment at any point before it completes.

A payment can have these statuses:

- **Draft:** the payment is created and not yet confirmed.
- **In Process:** you confirmed it and processing has begun.
- **Paid:** the payment was made and matched to a bill.
- **Not Paid:** the payment failed or is still unpaid.
- **Cancelled:** you cancelled it before processing.
- **Rejected:** it failed system checks or was declined.

### How bills are settled

A payment linked to a vendor bill is matched against that vendor's open bills.

- **Full payment:** the amount equals the bill total. The bill becomes **Paid**.
- **Partial payment:** the amount is less than the total. The bill becomes **Partially Paid**. Add more payments to finish.

You can also match payments manually.

::: tip Example
Create a **Send** payment of $2,500 linked to bill BILL/2025/05/207. Click **Confirm**. The payment moves to **In Process**. The system matches it to the bill. Both the bill and the payment become **Paid**.
:::

## See also

- [Create a bill](./create-bill.md)
- [Create a refund](./create-refund.md)
- [Manage vendors](./manage-vendors.md)
- [Bank accounts](../configuration/bank-accounts.md)
