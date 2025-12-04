# Vendor Payments

The **Vendor Payments** section in **AureusERP** allows you to efficiently manage outgoing payments to vendors, settle bills, and maintain accurate records of vendor transactions. Below is the **step-by-step** guide to creating a Vendor Payment.

## Payment Creation

### Steps to Create a New Payment

1. Navigate to **`Invoices → Vendors → Payments`** as shown in the image below.

   <ImagePopup src="/images1/invoices/vendor_payment_create_1.png" alt="Create Vendor Payment" />

2. Fill in the fields according to the following section:

   ### Payment Form Fields

   - **_Payment Type:_** (**_Send_** / **_Receive_**)
     - **_Send:_** Record outgoing payments to vendors (e.g., bill settlements).
     - **_Receive:_** Record refunds or payment returns from vendors.
   - **_Vendor:_** Choose from the list of registered vendors.
   - **_Amount:_** Enter the total amount being sent or received.
   - **_Vendor Bank Account:_** Select the bank account associated with the vendor.
   - **_Payment Method:_** Choose how the payment is made (Bank, Cash, Cheque, etc.).
   - **_Date:_** The date of the transaction.
   - **_Memo:_** Add optional notes or internal references.

   <ImagePopup src="/images1/invoices/vendor_payment_create_form.png" alt="Vendor Payment Form" />

## Payment Lifecycle & States

Once you click **Create**, the vendor payment record is saved and redirects to the **View Payment** page. The payment enters the **`Draft`** state.

### Payment States

- **_Draft_** – The initial state when the payment is created.
- **_In Process_** – After clicking **_Confirm_**, the payment begins processing.
- **_Paid_** – Indicates the payment was successfully made and reconciled with a bill.
- **_Not Paid_** – Indicates payment failed or remains unpaid.
- **_Cancelled_** – Payment was intentionally cancelled before processing.
- **_Rejected_** – The payment failed system checks or was declined.

## Available Actions (Post-Creation)

From the **View Payment** page, you can perform the following actions:

- **_Edit:_** Modify payment details (only available in the `Draft` state).
- **_Delete:_** Remove the payment before it is confirmed.
- **_Confirm:_** Move the payment to `In Process` and initiate payment settlement.
- **_Cancel:_** Cancel the payment at any point before completion.

   <ImagePopup src="/images1/invoices/vendor_payment_create_view.png" alt="Vendor Payment View" />

## Bill Settlement Logic

If a payment is linked to a vendor bill, AureusERP attempts to automatically reconcile it with open bills for the selected vendor.

- **Full Payment**: If the payment amount matches the bill total, the bill is marked as **Paid**.
- **Partial Payment**: If the payment is less than the total bill, the bill will be marked as **Partially Paid**. Additional payments can be added to complete the settlement.

Reconciliation is automatic based on vendor and open bill matching. Manual matching is also available if needed.

## Example Flow

1. **_Create Vendor Payment_**

   - **_Type:_** `Send`
   - **_Amount:_** `$2,500`
   - **_Linked to:_** `BILL/2025/05/207`

2. **_Confirm Payment_**

   - State changes to `In Process`

3. **_Automatic Bill Matching_**

   - The system matches the payment to `BILL/2025/05/207`.

4. **_Settlement Complete_**
   - Bill is marked as `Paid`
   - Payment status updated to `Paid`

## Summary

The **Vendor Payments** module in **AureusERP** provides a streamlined process for managing payments to vendors, ensuring accurate tracking and reconciliation with vendor bills. By following the outlined steps for creation, viewing, and confirmation, users can efficiently handle vendor payments while maintaining financial integrity within the system.
