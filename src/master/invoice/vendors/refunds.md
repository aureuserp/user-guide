# Refunds

The **Refunds** module in **AureusERP** allows users to manage vendor-side credit operations for returned goods or overpayments. It mirrors the vendor bill structure to ensure seamless processing and accurate record-keeping.

## Refund Creation

### Steps to Create a New Refund

1. Navigate to **`Invoices → Vendors → Refunds`** as shown in the image below.

  <ImagePopup src="/images1/invoices/refund_create_1.png" alt="Create Refund" />

2. Fill in the fields according to the following sections:

   ### General Section

   This section captures essential metadata for the refund:

   - **_Vendor:_** Select the supplier issuing the refund.
   - **_Bill Date:_** The date on which the refund document was issued by the vendor.
   - **_Bill Reference:_** Vendor’s credit note number or reference ID.
   - **_Accounting Date:_** Date for financial recognition of the refund.
   - **_Recipient Bank:_** Choose the vendor's bank account for payment receipt or offset.
   - **_Due Date:_** Set the payment deadline manually or calculate automatically based on payment terms.
   - **_Payment Term:_** Select a pre-defined duration for refund processing (e.g., Net 30, Immediate).
     > 🛈 When a payment term is selected, the **Due Date** field will be automatically replaced with the calculated date based on the selected term.

  <ImagePopup src="/images1/invoices/refund_create_general.png" alt="Create Refund" />

   ### Invoice Lines

   Use this section to enter the returned goods or services from the vendor.

   - **_Add Product:_** Click to add a refund line item. The following fields will appear:

     - **_Product:_** Choose the returned item or credited service.
     - **_Quantity:_** Specify the number of units or amount.
     - **_Unit:_** Define the unit of measure (e.g., Units, Dozens).
     - **_Taxes:_** Add applicable taxes involved in the return.
     - **_Discount Percentage:_** Apply discounts involved in the original bill.
     - **_Cost:_** Unit cost as per the bill.
     - **_Subtotal:_** Auto-calculated as `(Quantity × Cost - Discount) + Taxes`.

  <ImagePopup src="/images1/invoices/refund_create_invoicelines.png" alt="Create Refund" />

   ### Other Information

   - **Accounting**

     - **_Incoterm:_** Select applicable international trade terms (e.g., FOB, CIF).
     - **_Incoterm Location:_** Define the location tied to the selected Incoterm.

   - **Secured**

     - **_Payment Method:_** Specify how the refund will be processed.
     - **_Auto Post:_** Enable to automatically post the refund upon creation.
     - **_Checked:_** Toggle for internal review or approval.

   - **Additional Information**

     - **_Company:_** Select the company receiving the refund.
     - **_Currency:_** Choose the currency of the refund.

  <ImagePopup src="/images1/invoices/bill_create_other1.png" alt="Create Refund" />

3. **Action Buttons**

At the bottom of the form, the following actions are available:

- **_Create:_** Saves and creates the refund.
- **_Create & Create Another:_** Saves current refund and opens a fresh form.
- **_Cancel:_** Discards any entries and exits the refund creation screen.

## Refund View (Post-Creation)

After clicking **Create**, the system opens the **Refund View** page.

### Initial Actions (When Refund is in Draft)

- **_Edit:_** Open and modify refund fields.
- **_Confirm:_** Finalize the refund and change its status from **Draft** to **Posted**.
- **_Cancel:_** Mark the refund as cancelled.
- **_Delete:_** Remove the refund permanently.

<ImagePopup src="/images1/invoices/refund_view1.png" alt="View Refund" />

## Refund After Confirmation

Once the refund is **Confirmed** (status becomes Posted), the following actions become available:

- **_Pay:_** Opens a modal window with the following fields:

  - **_Amount:_** The refund amount to be received or adjusted.
  - **_Payment Date:_** Date the refund is expected or received.
  - **_Partner Bank Account:_** Select vendor's bank account from dropdown.
  - **_Payment Method:_** Choose from available refund methods.
  - **_Communication:_** Auto-filled Refund number (e.g., RBILL/2025/05/13).

  > 🛈 Clicking **Submit** updates refund status to **Paid**.
  > <ImagePopup src="/images1/invoices/refund_pay.png" alt="Create Refund" />

- **Reset to Draft**: Revert the refund back to **Draft** state.
- **Delete**: Remove the refund if needed.

<ImagePopup src="/images1/invoices/refund_confirm.png" alt="Confirmed Refund" />

## Summary

The **Refunds** module in **AureusERP** provides a structured approach to managing vendor refunds, ensuring accurate tracking and reconciliation with vendor bills. By following the outlined steps for creation, viewing, and confirmation, users can efficiently handle refund processes while maintaining financial integrity within the system.
