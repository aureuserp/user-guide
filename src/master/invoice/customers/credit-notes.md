# Credit Note

The **Credit Note** feature in **AureusERP** helps businesses manage refunds and invoice adjustments easily. You can use credit notes to:

- Cancel or correct an existing customer invoice

- Record product returns

## Credit Note Creation

### There are two ways to create a credit note:

1. From an Existing Invoice (automatic credit note creation)

2. Manually from the Credit Notes menu

### Method 1: Create Credit Note from an Invoice

Use this when you want to cancel or adjust a previously posted invoice.

### Steps to Create

1. Navigate to **`Invoices → Customers → Invoices`** as shown in the below image.

   ![Create Credit Note](/images1/invoices/creditnote.png)

2. Open the invoice you wish to adjust
3. Click on the Credit Note button
   ![Create Credit Note](/images1/invoices/creditnote_1.png)
4. Fill in the popup form with:

   - Reason for credit note
   - Date of credit note

5. Click Submit
   ![Create Credit Note](/images1/invoices/creditnote_modal.png)
6. A draft credit note will be created
   ![Create Credit Note](/images1/invoices/creditnote_savechanges.png)
7. Review and click Confirm to post it
   ![Create Credit Note](/images1/invoices/creditnote_confirm.png)

### Method 2: Create Credit Note Manually

Use this when:

- You’re issuing a refund not linked to a specific invoice

- You want to manually enter the returned products or custom values

### Steps to Create

1. Navigate to **`Invoices → Customers → Credit Notes → New Credit Note`** as shown in the below image.

   ![Create Credit Note](/images1/invoices/creditnote_create.png)

2. Fill in the form as per the following sections:

   ### General Section

   This section collects general information about the credit note.

   - **_Customer:_** Select the customer from the dropdown list.
   - **_Invoice Date:_** Set the creation date of the credit note.
   - **_Due Date:_** Enter the due date for applying the credit.
   - **_Payment Term:_** Choose a payment term from the dropdown (e.g., Net 15, Immediate).
     > 🛈 Selecting a payment term will replace the **Due Date** field with an auto-calculated one based on the term.

   ![Create Credit Note](/images1/invoices/creditnote_general.png)

   ### Invoice Lines

   - Click the **Add Product** button to add line items. The following fields will appear:

     - **_Product:_** Select the product to be credited.
     - **_Quantity:_** Enter the quantity.
     - **_Unit:_** Choose from **Units** or **Dozens**.
     - **_Taxes:_** Apply applicable tax rates.
     - **_Discount Percentage:_** Apply any discount.
     - **_Unit Price:_** Unit price of the product.
     - **_Subtotal:_** Auto-calculated value `(Quantity x Unit Price - Discount) + Taxes`.

     ![Create Credit Note](/images1/invoices/creditnote_invoiceline.png)

   ### Other Information

   - **Invoice**

     - **_Sales Person:_** Select the responsible user.
     - **_Customer Reference:_** Enter customer-side reference.
     - **_Recipient Bank:_** Choose a bank account.
     - **_Payment Reference:_** Optional payment transaction reference.
     - **_Delivery Date:_** Enter delivery date if applicable.

     ![Create Credit Note](/images1/invoices/creditnote_other.png)

   - **Accounting**

     - **_Incoterm:_** Choose international trade terms.
     - **_Incoterm Location:_** Enter specific location.
     - **_Payment Method:_** Select the mode of refund.
     - **_Auto Post:_** Toggle to automatically post the credit note.
     - **_Checked:_** Toggle to mark for review.

     ![Other Info - Accounting](/images1/invoices/creditnote_accounting.png)

   - **Additional Information**

     - **_Company:_** Select issuing company (multi-company supported).
     - **_Currency:_** Default is USD but can be changed.

     ![Other Info - Additional](/images1/invoices/creditnote_additional.png)

   - **Marketing**

     - **_Campaign:_** Link a marketing campaign if applicable.
     - **_Medium:_** Specify marketing medium.
     - **_Source:_** Identify lead source.

     ![Other Info - Marketing](/images1/invoices/creditnote_marketing.png)

3. **Action Buttons**

   At the bottom of the form, you will find:

   - **_Create:_** Save and create the credit note.
   - **_Create & Create Another:_** Save and open a new blank credit note.
   - **_Cancel:_** Exit without saving.

## Credit Note View (Post-Creation)

After clicking **Create**, the system redirects to the **Credit Note View** page.

### Initial Actions (While in Draft)

- **_Edit:_** Modify credit note.
- **_Confirm:_** Finalize and post the credit note.
- **_Cancel:_** Mark the credit note as cancelled.
- **_Delete:_** Remove the credit note.

![Create Invoice](/images1/invoices/creditnote_view.png)

## Credit Note After Confirmation

Once the credit note is **confirmed**, the following options become available:

- **_Pay:_** Opens a modal window with fields:

  - **_Amount:_** The credit amount.
  - **_Payment Date:_** Date of refund.
  - **_Partner Bank Account:_** Select a bank account.
  - **_Payment Method:_** Choose a refund method.
  - **_Communication:_** Credit note number (e.g., RINV/2025/05/13).

  > 🛈 Clicking **Submit** will update the credit note’s status to **Paid**.
  > ![Create Invoice](/images1/invoices/creditnote_paymodal.png)

- **_Reset to Draft:_** Reverts the credit note to editable draft mode.
- **_Preview:_** Opens a printable version of the credit note.
- **_Delete:_** Removes the credit note permanently.

![Create Invoice](/images1/invoices/creditnote_pay.png)

## Summary

The **Credit Note** feature in **AureusERP** streamlines the process of issuing refunds and adjustments to customer invoices. Whether created from an existing invoice or manually, credit notes can be customized with detailed line items, accounting information, and marketing data. The intuitive interface allows for easy management of credit notes through various actions such as editing, confirming, paying, and deleting. This ensures that businesses can maintain accurate financial records while providing excellent customer service.
