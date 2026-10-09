# Create a credit note

A **credit note** reduces or cancels an invoice you already issued. Use it to correct a billing mistake, cancel an invoice or record a product return. It keeps your accounts accurate without deleting the original invoice.

> **In simple words:** A credit note is the opposite of an invoice. It gives money or credit back to the customer.

You can create a credit note in two ways: from an existing invoice, or manually.

## Create from an invoice

Use this to cancel or adjust a posted invoice.

1. Go to `Invoices → Customers → Invoices`.

   <ImagePopup src="/images1/invoices/creditnote.png" alt="Invoices list used to find the invoice to credit" />

2. Open the invoice.
3. Click **Credit Note**.

   <ImagePopup src="/images1/invoices/creditnote_1.png" alt="Credit Note button on the invoice" />

4. Fill in the modal:
   - **Reason:** Enter why you issue the credit note.
   - **Date:** Enter the credit note date.
5. Click **Submit**.

   <ImagePopup src="/images1/invoices/creditnote_modal.png" alt="Credit note modal with reason and date" />

6. Check the draft credit note that opens.

   <ImagePopup src="/images1/invoices/creditnote_savechanges.png" alt="Draft credit note created from the invoice" />

7. Click **Confirm** to post it.

   <ImagePopup src="/images1/invoices/creditnote_confirm.png" alt="Confirm button on the draft credit note" />

## Create manually

Use this for a refund that is not linked to an invoice, or to enter returned products yourself.

1. Go to `Invoices → Customers → Credit Notes` and click **New Credit Note**.

   <ImagePopup src="/images1/invoices/creditnote_create.png" alt="Credit Notes list with the New Credit Note button" />

2. Fill in the form sections below.

### General

- **_Customer:_** Select the customer.
- **_Invoice Date:_** Set the credit note date.
- **_Due Date:_** Enter the due date for applying the credit.
- **_Payment Term:_** Select a term, for example Net 15 or Immediate.

::: info
When you select a payment term, the **Due Date** is replaced by a date calculated from the term.
:::

<ImagePopup src="/images1/invoices/creditnote_general.png" alt="Credit note form, General section" />

### Invoice lines

Click **Add Product** to add a line. Each line has these fields:

- **_Product:_** Select the product to credit.
- **_Quantity:_** Enter the quantity.
- **_Unit:_** Select **Units** or **Dozens**.
- **_Taxes:_** Select the tax rates that apply.
- **_Discount Percentage:_** Enter a discount, if any.
- **_Unit Price:_** Enter the price per unit.
- **_Subtotal:_** Calculated for you as `(Quantity x Unit Price - Discount) + Taxes`.

<ImagePopup src="/images1/invoices/creditnote_invoiceline.png" alt="Credit note form, Invoice Lines" />

### Other information

Under **Invoice**:

- **_Sales Person:_** Select the responsible user.
- **_Customer Reference:_** Enter the customer's reference.
- **_Recipient Bank:_** Select a bank account.
- **_Payment Reference:_** Enter an optional payment reference.
- **_Delivery Date:_** Enter the delivery date, if it applies.

<ImagePopup src="/images1/invoices/creditnote_other.png" alt="Credit note form, Other Information, Invoice tab" />

Under **Accounting**:

- **_Incoterm:_** Select the international trade terms.
- **_Incoterm Location:_** Enter the specific location.
- **_Payment Method:_** Select how you refund.
- **_Auto Post:_** Turn on to post the credit note automatically.
- **_Checked:_** Turn on to mark the credit note as reviewed.

<ImagePopup src="/images1/invoices/creditnote_accounting.png" alt="Credit note form, Other Information, Accounting tab" />

Under **Additional Information**:

- **_Company:_** Select the issuing company.
- **_Currency:_** Select the currency. USD is the default.

<ImagePopup src="/images1/invoices/creditnote_additional.png" alt="Credit note form, Other Information, Additional Information tab" />

Under **Marketing**:

- **_Campaign:_** Link a marketing campaign.
- **_Medium:_** Enter the marketing medium.
- **_Source:_** Enter the lead source.

<ImagePopup src="/images1/invoices/creditnote_marketing.png" alt="Credit note form, Other Information, Marketing tab" />

3. Click a button at the bottom of the form:
   - **Create:** Save the credit note.
   - **Create & Create Another:** Save it and open a blank form.
   - **Cancel:** Exit without saving.

## Actions and statuses

After you click **Create**, the credit note opens in draft.

<ImagePopup src="/images1/invoices/creditnote_view.png" alt="Draft credit note with Edit, Confirm, Cancel and Delete buttons" />

In draft:

- **Edit:** Change the credit note.
- **Confirm:** Post the credit note.
- **Cancel:** Mark it as cancelled.
- **Delete:** Remove it.

After you confirm the credit note:

- **Pay:** Open a modal and record the refund.
- **Reset to Draft:** Make the credit note editable again.
- **Preview:** Open a printable version.
- **Delete:** Remove it.

<ImagePopup src="/images1/invoices/creditnote_pay.png" alt="Confirmed credit note with Pay, Reset to Draft, Preview and Delete buttons" />

The **Pay** modal has these fields:

- **_Amount:_** The credit amount.
- **_Payment Date:_** The refund date.
- **_Partner Bank Account:_** The bank account.
- **_Payment Method:_** The refund method.
- **_Communication:_** The credit note number, for example RINV/2025/05/13.

Click **Submit** to change the credit note status to **Paid**.

<ImagePopup src="/images1/invoices/creditnote_paymodal.png" alt="Pay modal on a confirmed credit note" />

## See also

- [Create an invoice](./create-invoice.md)
- [Register a payment](./register-payment.md)
- [Manage customers](./manage-customers.md)
- [Create a refund (vendors)](../vendors/create-refund.md)
