# Bills

The **Bills** module in **AureusERP** is designed to help businesses accurately record and manage vendor expenses and obligations. It enables finance teams to track purchases, validate vendor bills, and prepare for timely payments.

## Bill Creation

### Steps to Create a New Bill

1. Navigate to **`Invoices → Vendors → Bills`** as shown in the image below.

  <ImagePopup src="/images1/invoices/bill_create_1.png" alt="Create Bill" />

2. Fill in the fields according to the following sections:

   ### General Section

   This section captures essential metadata for the vendor bill:

   - **_Vendor:_** Select the supplier who issued the bill.
   - **_Bill Date:_** The date on which the bill was issued by the vendor.
   - **_Bill Reference:_** Vendor’s invoice number or reference ID.
   - **_Accounting Date:_** Date for financial recognition of the bill.
   - **_Payment Reference:_** Add a reference string or transaction ID for internal tracking.
   - **_Recipient Bank:_** Choose the vendor's bank account for payment.
   - **_Due Date:_** Set the payment deadline manually or calculate automatically based on payment terms.
   - **_Payment Term:_** Select a pre-defined duration for when the bill should be paid (e.g., Net 30, Immediate).
     > 🛈 When a payment term is selected, the **Due Date** field will be automatically replaced with the calculated date based on the selected term.

  <ImagePopup src="/images1/invoices/bill_create_general.png" alt="Create Bill" />

   ### Invoice Lines

   Use this section to enter purchased goods or services from the vendor.

   - **_Add Product:_** Click to add a bill line item. The following fields will appear:

     - **_Product:_** Choose the purchased item or service.
     - **_Quantity:_** Specify the number of units or amount.
     - **_Unit:_** Define the unit of measure (e.g., Units, Dozens).
     - **_Taxes:_** Add applicable vendor-side taxes.
     - **_Discount Percentage:_** Apply negotiated discounts.
     - **_Cost:_** unit price of the product.
     - **_Subtotal:_** Auto-calculated as `(Quantity × Cost - Discount) + Taxes`.

  <ImagePopup src="/images1/invoices/vendor_create_invoicelines.png" alt="Create Bill" />

   ### Other Information

   - **Accounting**

     - **_Incoterm:_** Select applicable international trade terms (e.g., FOB, CIF).
     - **_Incoterm Location:_** Define the location tied to the selected Incoterm.

   - **Secured**

     - **_Payment Method:_** Specify the method of vendor payment (e.g., Wire Transfer).
     - **_Auto Post:_** Enable to automatically post the bill upon creation.
     - **_Checked:_** Toggle for internal review or approval.

   - **Additional Information**

     - **_Company:_** Select the company paying the bill (for multi-company setup).
     - **_Currency:_** Choose the currency of the bill.

  <ImagePopup src="/images1/invoices/bill_create_other.png" alt="Create Bill" />

3. **Action Buttons**

At the bottom of the form, the following actions are available:

- **_Create:_** Saves and creates the bill.
- **_Create & Create Another:_** Saves current bill and opens a fresh form.
- **_Cancel:_** Discards any entries and exits the bill creation screen.

## Bill View (Post-Creation)

After clicking **Create**, the system opens the **Bill View** page.

### Initial Actions (When Bill is in Draft)

- **_Edit:_** Open and modify bill fields.
- **_Confirm:_** Finalize the bill and change its status from **Draft** to **Posted**.
- **_Cancel:_** Mark the bill as cancelled.
- **_Delete:_** Remove the bill permanently.

<ImagePopup src="/images1/invoices/bill_view.png" alt="View Bill" />

## Bill After Confirmation

Once the bill is **Confirmed** (status becomes Posted), the following actions become available:

- **_Pay:_** Opens a modal window with the following fields:

  - **_Amount:_** The bill amount to be paid.
  - **_Payment Date:_** Date of payment.
  - **_Partner Bank Account:_** Select bank account from dropdown.
  - **_Payment Method:_** Choose from available methods.
  - **_Communication:_** Auto-filled Bill number (e.g., BILL/2025/05/13).

  > 🛈 Clicking **Submit** updates bill status to **Paid**.
  > <ImagePopup src="/images1/invoices/bill_pay.png" alt="Create Invoice" />

- **_Reset to Draft:_** Revert the bill back to **Draft** state.
- **_Credit Note:_** Create a credit note with **Reason** and **Date**.
- **_Delete:_** Remove the bill if needed.

<ImagePopup src="/images1/invoices/bill_confirm.png" alt="Create Invoice" />

## Summary

The **Bills** module in **AureusERP** streamlines vendor expense management by providing tools to create, track, and settle bills efficiently. By following the outlined steps, finance teams can ensure accurate recording of vendor obligations, timely payments, and maintain healthy supplier relationships.
