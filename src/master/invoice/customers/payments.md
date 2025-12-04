# Payments

The **Payments** section in AureusERP enables you to efficiently record and manage customer payments, handle invoice settlements, and monitor transaction states just like a standard ERP workflow. Below is the **step-by-step** guide to creating an Payment.

## Payment Creation

### Steps to Create a New Payment

1. Navigate to **`Invoices → Customers → Payments`** as shown in the below image.

<ImagePopup src="/images1/invoices/payment_create_1.png" alt="Create Payment" />

2.  Fill up the fields as per the **sections** defined below.

### Payment Form Fields

- **_Payment Type_** (**_Send_** / **_Receive_**)
  - **_Receive:_** Record incoming payments from customers (e.g., invoice payments).
  - **_Send:_** Record outgoing payments (e.g., refunds to customers).
- **_Customer:_** Choose from the list of existing customers.
- **_Amount:_** Enter the total amount being sent or received.
- **_Customer Bank Account:_** Select the bank account associated with the customer.
- **_Payment Method:_** Choose how the payment is made (Bank, Cash, Cheque, etc.).
- **_Date:_** The date of the transaction.
- **_Memo:_** Add optional notes or references for internal use.

<ImagePopup src="/images1/invoices/payment_create_form.png" alt="Create Payment" />

## Payment Lifecycle & States

Once you click **Create**, the payment record is saved and redirects to the **View Payment** page. The payment enters the **`Draft`** state.

### Payment States

- **_Draft_** – The initial state when the payment is created.
- **_In Process_** – After clicking **Confirm**, the payment starts processing.
- **_Paid_** – Indicates that the payment was successfully completed and matched to an invoice.
- **_Not Paid_** – Used if the payment fails or is marked as unpaid.
- **_Cancelled_** – The payment was intentionally cancelled before completion.
- **_Rejected_** – The payment was declined or failed system validation.

## Available Actions (Post-Creation)

From the **View Payment** page, you can perform the following actions:

- **_Edit:_** Modify payment details (available in `Draft` state only).
- **_Delete:_** Remove the payment entry before confirmation.
- **_Confirm:_** Move the payment to `In Process` and begin settlement.
- **_Cancel:_** Cancel the payment at any time before it becomes `Paid`.

<ImagePopup src="/images1/invoices/payment_create_view.png" alt="Create Payment" />

## Invoice Settlement Logic

If a payment is linked to a customer invoice, the system attempts to automatically reconcile the payment with any open invoices associated with the selected customer.

- **Full Payment**: If the payment amount matches the invoice total, the invoice is marked as **_Paid_**.
- **Partial Payment**: If less than the total is paid, the invoice shows as **_Partially Paid_**. You can settle the remaining balance with another payment later.

Reconciliation happens automatically based on customer and open invoice matching. Manual reconciliation can be handled separately if needed.

## Example Flow

1. **_Create Payment_**

   - **_Type:_** `Receive`
   - **_Amount:_** `$1,000`
   - **_Linked to:_** `INV/2025/05/101`

2. **_Confirm Payment_**

   - State changes to `In Process`

3. **_Automatic Invoice Matching_**

   - The system finds `INV/2025/05/101` and applies the payment.

4. **_Settlement Complete_**
   - Invoice marked as `Paid`
   - Payment status updated to `Paid`
