# Register a payment

A **payment** records money you receive from a customer, or money you send back to them. It settles open invoices and keeps your bank and customer balances accurate.

> **In simple words:** A payment is the record that says a customer paid, or that you paid them.

## Create a payment

1. Go to `Invoices → Customers → Payments` and click **New Payment**.

   <ImagePopup src="/images1/invoices/payment_create_1.png" alt="Payments list with the New Payment button" />

2. Fill in the form:
   - **_Payment Type:_** Choose **Receive** for money from a customer, such as an invoice payment. Choose **Send** for money to a customer, such as a refund.
   - **_Customer:_** Select the customer.
   - **_Amount:_** Enter the amount sent or received.
   - **_Customer Bank Account:_** Select the customer's bank account.
   - **_Payment Method:_** Select how the payment is made, for example Bank, Cash or Cheque.
   - **_Date:_** Enter the transaction date.
   - **_Memo:_** Add an optional internal note or reference.

   <ImagePopup src="/images1/invoices/payment_create_form.png" alt="Payment form with type, customer, amount and method" />

3. Click **Create**. The payment opens in **Draft** status.

## Actions and statuses

<ImagePopup src="/images1/invoices/payment_create_view.png" alt="View Payment page with Edit, Delete, Confirm and Cancel buttons" />

Use these buttons on the **View Payment** page:

- **Edit:** Change the payment. Available in **Draft** only.
- **Delete:** Remove the payment before you confirm it.
- **Confirm:** Move the payment to **In Process** and start settlement.
- **Cancel:** Cancel the payment at any time before it is **Paid**.

A payment can have these statuses:

- **Draft:** The payment was just created.
- **In Process:** You confirmed the payment and it is being processed.
- **Paid:** The payment is complete and matched to an invoice.
- **Not Paid:** The payment failed or was marked as unpaid.
- **Cancelled:** The payment was cancelled before completion.
- **Rejected:** The payment was declined or failed validation.

## How invoices are settled

When a payment is linked to a customer, the system tries to match it with that customer's open invoices.

- **Full payment:** The payment equals the invoice total. The invoice becomes **Paid**.
- **Partial payment:** The payment is less than the total. The invoice shows as **Partially Paid**. Register another payment for the balance.

::: info
Matching uses the customer and the open invoices. Manual reconciliation is handled separately.
:::

### Example

1. Create a payment of type **Receive** for 1,000, linked to invoice INV/2025/05/101.
2. Click **Confirm**. The status changes to **In Process**.
3. The system finds INV/2025/05/101 and applies the payment.
4. The invoice and the payment both change to **Paid**.

::: tip
You can also pay straight from a confirmed invoice with its **Pay** button. See [Create an invoice](./create-invoice.md).
:::

## See also

- [Create an invoice](./create-invoice.md)
- [Create a credit note](./create-credit-note.md)
- [Manage customers](./manage-customers.md)
- [Register a vendor payment](../vendors/register-payment.md)
- [Bank accounts](../configuration/bank-accounts.md)
