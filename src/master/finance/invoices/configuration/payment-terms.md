# Payment terms

A payment term sets when an invoice or bill is due. It can also offer a discount for early payment. This gives customers and vendors a clear deadline and helps your cash flow.

> **In simple words:** A payment term tells the app how many days someone has to pay.

## Create a payment term

1. Go to `Invoices → Configurations → Payment Terms`.
2. Click **New Payment Terms**.

   <ImagePopup src="/images1/invoices/payment_term_create.png" alt="Payment Terms list with the New Payment Terms button" />

3. Fill in the form.

   - **_Payment Term:_** Enter a name, such as Net 30 or Immediate.
   - **_Early Discount:_** Turn on to offer a discount for early payment.
   - **_Discount Percentage:_** Enter the discount. Shown when **Early Discount** is on.
   - **_Number of Days to Pay:_** Enter the days allowed for the discount. Shown when **Early Discount** is on.
   - **_Reduced Tax:_** Choose **On Early Payment**, **Never** or **Always (upon Invoice)**.

   <ImagePopup src="/images1/invoices/payment_terms_create_1.png" alt="Payment term form with early discount and reduced tax options" />

4. Save the term. The view page opens, where you manage due terms.

## Manage due terms

1. On the payment term view page, click **Manage Due Terms**.
2. Check the default due term. It has a value of 100%.
3. Click **New Payment Due Term**. A modal opens.

   <ImagePopup src="/images1/invoices/due_terms_create_1.png" alt="Due terms management screen with the default 100 percent term" />

4. Fill in the fields.

   - **_Value:_** Enter a percentage or fixed value.
   - **_Due:_** Enter a description or label.
   - **_Delay Type:_** Choose **Day After**, **Day After End of Month**, **Day After End of Next Month** or **Days End of Month On**.
   - **_Days on the Next Month:_** Enter the day. Used for the monthly delay types.
   - **_Days:_** Enter the number of days for the delay.
   - **_Payment Term:_** Select the payment term this due term belongs to.

   <ImagePopup src="/images1/invoices/due_terms_create.png" alt="New payment due term modal with value, delay type and days" />

5. Save the due term.

::: info
The app uses payment terms to calculate due dates and discounts on invoices and bills.
:::

## See also

- [Create an invoice](../customers/create-invoice.md)
- [Create a bill](../vendors/create-bill.md)
- [Configuration overview](./index.md)
