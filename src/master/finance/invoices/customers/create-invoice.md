# Create an invoice

An **invoice** is the bill you send to a customer for products or services. It records who owes what, by when, and under which accounting terms. Create one for every sale you want to collect payment for.

> **In simple words:** An invoice asks a customer to pay you. It starts as a draft and becomes final when you confirm it.

## Create an invoice

1. Go to `Invoices → Customers → Invoices` and click **New Invoice**.

   <ImagePopup src="/images1/invoices/invoices.png" alt="Invoices list with the New Invoice button" />

2. Fill in the form sections below.

### General

- **_Customer:_** Select the customer you bill.
- **_Invoice Date:_** Choose the date of the invoice.
- **_Due Date:_** Set the payment deadline.
- **_Payment Term:_** Select a term, for example Net 30 or Immediate.

::: info
When you select a payment term, the **Due Date** is replaced by a date calculated from the term.
:::

<ImagePopup src="/images1/invoices/invoices_create.png" alt="Invoice form, General section" />

### Invoice lines

Click **Add Product** to add a line. Each line has these fields:

- **_Product:_** Select the product or service.
- **_Quantity:_** Enter the number of units or dozens.
- **_Unit:_** Select **Units** or **Dozens**.
- **_Taxes:_** Select the tax rates that apply.
- **_Discount Percentage:_** Enter a discount, if any.
- **_Unit Price:_** Enter the price per unit.
- **_Subtotal:_** Calculated for you as `(Quantity x Unit Price - Discount) + Taxes`.

<ImagePopup src="/images1/invoices/invoices_product.png" alt="Invoice form, Invoice Lines with a product line" />

### Other information

Under **Invoice**:

- **_Sales Person:_** Select the sales representative.
- **_Customer Reference:_** Enter the customer's own reference, if any.
- **_Recipient Bank:_** Select the bank account that receives payment.
- **_Payment Reference:_** Enter a payment reference code.
- **_Delivery Date:_** Enter the expected or actual delivery date.

<ImagePopup src="/images1/invoices/invoices_other.png" alt="Invoice form, Other Information, Invoice tab" />

Under **Accounting**:

- **_Incoterm:_** Select the international commercial terms, for example FOB or CIF.
- **_Incoterm Location:_** Enter the place tied to the Incoterm.
- **_Payment Method:_** Select how the customer plans to pay.
- **_Auto Post:_** Turn on to post the invoice when it is created.
- **_Checked:_** Turn on to mark the invoice as reviewed.

<ImagePopup src="/images1/invoices/invoices_accounting.png" alt="Invoice form, Other Information, Accounting tab" />

Under **Additional Information**:

- **_Company:_** Select the issuing company.
- **_Currency:_** Select the invoice currency. USD is the default.

<ImagePopup src="/images1/invoices/invoices_additional.png" alt="Invoice form, Other Information, Additional Information tab" />

Under **Marketing**:

- **_Campaign:_** Link a marketing campaign.
- **_Medium:_** Enter the medium, for example Email or Social Media.
- **_Source:_** Enter the source, for example Google or Referral.

<ImagePopup src="/images1/invoices/invoices_marketing.png" alt="Invoice form, Other Information, Marketing tab" />

3. Click a button at the bottom of the form:
   - **Create:** Save the invoice.
   - **Create & Create Another:** Save it and open a blank form.
   - **Cancel:** Discard the changes.

## Actions and statuses

After you click **Create**, the invoice opens in **Draft** status.

<ImagePopup src="/images1/invoices/invoices_view.png" alt="Draft invoice with Edit, Confirm, Cancel and Delete buttons" />

In **Draft**:

- **Edit:** Change the invoice fields.
- **Confirm:** Change the status from **Draft** to **Posted**.
- **Cancel:** Mark the invoice as cancelled.
- **Delete:** Remove the invoice.

After you confirm the invoice:

- **Pay:** Open a modal and record the payment.
- **Reset to Draft:** Return the invoice to **Draft**.
- **Preview:** Open a printable version.
- **Credit Note:** Create a credit note with a **Reason** and a **Date**.
- **Delete:** Remove the invoice.

<ImagePopup src="/images1/invoices/invoices_pay.png" alt="Confirmed invoice with Pay, Reset to Draft, Preview, Credit Note and Delete buttons" />

The **Pay** modal has these fields:

- **_Amount:_** The amount to pay.
- **_Payment Date:_** The date of payment.
- **_Partner Bank Account:_** The bank account.
- **_Payment Method:_** The method used.
- **_Communication:_** The invoice number, filled in for you, for example INV/2025/05/13.

Click **Submit** to change the invoice status to **Paid**.

<ImagePopup src="/images1/invoices/invoices_pay_modal.png" alt="Pay modal on a confirmed invoice" />

## See also

- [Manage customers](./manage-customers.md)
- [Create a credit note](./create-credit-note.md)
- [Register a payment](./register-payment.md)
- [Manage products](../products/manage-products.md)
- [Taxes](../configuration/taxes.md)
- [Payment terms](../configuration/payment-terms.md)
- [Incoterms](../configuration/incoterms.md)
