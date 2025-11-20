# Invoices

The Invoice module in **AureusERP** allows users to generate professional invoices with detailed control over billing, product lines, accounting standards, and marketing insights.

Below is the **step-by-step** guide to creating an invoice.

## Invoice Creation

### Steps to Create a New Invoice

1.  Navigate to **`Invoices → Customers → New Invoice`** as shown in the below image.

    ![Create Invoice](/images1/invoices/invoices.png)

2.  Fill up the fields as per the **sections** defined below.

    ### General Section

    This section captures the basic invoice metadata.

    - **_Customer:_** Select the customer to whom the invoice will be issued.
    - **_Invoice Date:_** Choose the date of invoice generation.
    - **_Due Date:_** Set the deadline for payment.
    - **_Payment Term:_** Select a predefined payment term (e.g., Net 30, Immediate).
      > 🛈 When a payment term is selected, the **Due Date** field will be automatically replaced with the calculated date based on the selected term.

    ![Create Invoice](/images1/invoices/invoices_create.png)

    ### Invoice Lines

    Use this section to add products or services being billed.

    - **_Add Product:_** Click to add a new invoice line. The following fields will appear:

      - **_Product:_** Select the product or service.
      - **_Quantity:_** Enter the number of units or dozens.
      - **_Unit:_** Select **Units** or **Dozens**.
      - **_Taxes:_** Specify applicable tax rates.
      - **_Discount Percentage:_** Apply discount if applicable.
      - **_Unit Price:_** Input price per unit.
      - **_Subtotal:_** Automatically calculated as `(Quantity x Unit Price - Discount) + Taxes`.

    ![Create Invoice](/images1/invoices/invoices_product.png)

    ### Other Information

    - **Invoice Subsection**

      - **_Sales Person:_** Select a user acting as the sales representative.
      - **_Customer Reference:_** Enter customer’s internal reference (if any).
      - **_Recipient Bank:_** Select the customer’s receiving bank account.
      - **_Payment Reference:_** Add a payment transaction or reference code.
      - **_Delivery Date:_** Mention the expected or actual delivery date.

      ![Create Invoice](/images1/invoices/invoices_other.png)

    - **Accounting**

      - **_Incoterm:_** Select international commercial terms (e.g., FOB, CIF).
      - **_Incoterm Location:_** Specify the geographical location tied to the Incoterm.
      - **_Payment Method:_** Define how the customer intends to pay (e.g., Credit Card, Wire Transfer).
      - **_Auto Post:_** Enable to automatically post this invoice upon creation.
      - **_Checked:_** Use for internal review or verification before processing.

      ![Create Invoice](/images1/invoices/invoices_accounting.png)

    - **Additional Information**

      - **_Company:_** Select the company issuing the invoice (multi-company support).
      - **_Currency:_** Choose the currency for the invoice. USD is selected by default.

      ![Create Invoice](/images1/invoices/invoices_additional.png)

    - **Marketing**

      - **_Campaign:_** Tag this invoice with an associated marketing campaign.
      - **_Medium:_** Identify the medium (e.g., Email, Social Media).
      - **_Source:_** Specify the source (e.g., Google, Referral).

      ![Create Invoice](/images1/invoices/invoices_marketing.png)

3.  **Action Buttons**

    At the bottom of the form, you will find:

    - **_Create:_** Saves and creates the invoice.
    - **_Create & Create Another:_** Saves current invoice and opens a new invoice form.
    - **_Cancel:_** Discards the changes and exits the invoice creation screen.

## Invoice View (Post-Creation)

After clicking **Create**, the system redirects to the **Invoice View** page.

### Initial Actions (When Invoice is in Draft)

- **_Edit:_** Modify invoice fields.
- **_Confirm:_** Finalize the invoice and change its status from **Draft** to **Posted**.
- **_Cancel:_** Mark the invoice as cancelled.
- **_Delete:_** Permanently remove the invoice.

![Create Invoice](/images1/invoices/invoices_view.png)

## Invoice After Confirmation

Once the invoice is **Confirmed** (status becomes Posted), the following actions become available:

- **_Pay:_** Opens a modal window with the following fields:

  - **_Amount:_** The invoice amount to be paid.
  - **_Payment Date:_** Date of payment.
  - **_Partner Bank Account:_** Select bank account from dropdown.
  - **_Payment Method:_** Choose from available methods.
  - **_Communication:_** Auto-filled invoice number (e.g., INV/2025/05/13).

  > 🛈 Clicking **Submit** updates invoice status to **Paid**.
  > ![Create Invoice](/images1/invoices/invoices_pay_modal.png)

- **_Reset to Draft:_** Revert the invoice back to **Draft** state.
- **_Preview:_** Display a printable version of the invoice.
- **_Credit Note:_** Create a credit note with **Reason** and **Date**.
- **_Delete:_** Remove the invoice if needed.

![Create Invoice](/images1/invoices/invoices_pay.png)

## Summary

The **Invoice** module in **AureusERP** allows users to generate professional invoices with detailed control over billing, product lines, accounting standards, and marketing insights. By following the steps outlined in this guide, users can efficiently create and manage invoices, ensuring accurate billing and record-keeping.
