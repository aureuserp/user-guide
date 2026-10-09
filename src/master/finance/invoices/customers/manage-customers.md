# Manage customers

A **customer** is a person or company you sell to. The record stores contact, tax, payment and invoicing details. You need a customer before you can create an invoice or credit note.

> **In simple words:** A customer record is the address book entry that every invoice points to.

## Create a customer

1. Go to `Invoices → Customers → Customers` and click **New Customer**.

   <ImagePopup src="/images1/invoices/customer.png" alt="Customers list with the New Customer button" />

2. Fill in the form sections below.

### General

- **_Individual or Company:_** Choose the customer type. If you choose **Company**, the **Company** field is hidden.
- **_Name:_** Enter the full name of the person or contact.
- **_Company:_** Select or create the related company, if any.
- **_Tax ID:_** Enter the official tax identification number.
- **_Job Title:_** Enter the person's job title.
- **_Phone:_** Enter the main landline number.
- **_Mobile:_** Enter a mobile number for urgent contact.
- **_Email:_** Enter the address used for communication and invoicing.
- **_Website:_** Enter the customer's website.
- **_Title:_** Select or create a prefix such as Mr., Ms. or Dr.
- **_Tags:_** Pick existing tags or create new ones to label the customer.
- **_Address:_** Enter the street, city, zip code, state and country.

<ImagePopup src="/images1/invoices/customer_general.png" alt="Customer form, General section" />

### Sales and Purchase

Under **Sales**:

- **_Sales Person:_** Select the internal user who owns this customer.
- **_Payment Terms:_** Set how long the customer has to pay, for example Net 30 or Immediate.
- **_Payment Method:_** Set the preferred way the customer pays you.

Under **Purchase**:

- **_Payment Terms:_** Set the default payment timeline when you buy from this customer.
- **_Payment Method:_** Set how you pay this customer if they are also a vendor.

<ImagePopup src="/images1/invoices/customer_sales.png" alt="Customer form, Sales and Purchase section" />

Under **Fiscal Information**:

- **_Fiscal Position:_** Select the tax and accounting rules that apply, often based on location.

Under **Others**:

- **_Company ID:_** Enter an internal reference code for this customer.
- **_Reference:_** Enter a secondary code, such as a customer code.
- **_Industry:_** Select the customer's business sector. It helps with reporting.

<ImagePopup src="/images1/invoices/customer_others.png" alt="Customer form, Fiscal Information and Others subsections" />

### Invoicing

Under **Customer Invoices**:

- **_Invoice Sending Method:_** Choose **Download**, **Email** or **Post**.
- **_eInvoice Format:_** Select the electronic invoice format your region requires.

Under **Automation**:

- **_Auto Post Bills:_** Choose **Always**, **Ask after 3 validations without edit** or **Never**.
- **_Ignore Abnormal Invoice Amount:_** Turn on to skip warnings for unusually high or low amounts.
- **_Ignore Abnormal Invoice Date:_** Turn on to skip warnings for suspicious invoice dates.

<ImagePopup src="/images1/invoices/customer_invoicing.png" alt="Customer form, Invoicing section" />

3. Click **Create**. The customer opens on the **View Partner** page.

## Actions and statuses

On the **View Partner** page, you can edit the customer and manage related records.

<ImagePopup src="/images1/invoices/customer_view.png" alt="View Partner page of a customer" />

- **Edit Partner:** Update personal, company or fiscal details.

### Contacts

1. Open the **Contacts** tab.
2. Click **Add Contact**.
3. Fill in the modal, which uses the same fields as the customer form, such as name, email, phone and title.

<ImagePopup src="/images1/invoices/customer_contacts.png" alt="Add Contact modal on the customer record" />

::: tip
Add several contacts when a customer has more than one person to deal with.
:::

### Address

1. Open the **Address** tab.
2. Click **Add Address**.
3. Turn on the address type: **Permanent**, **Present**, **Invoice**, **Delivery** or **Other**.
4. Enter **Name**, **Email**, **Phone**, **Mobile** and the full address (street, city, zip code, state, country).

<ImagePopup src="/images1/invoices/customer_address.png" alt="Add Address modal on the customer record" />

### Bank accounts

1. Open the **Bank Account** section.
2. Click **New Bank Account**.
3. Fill in the modal:
   - **_Account Number:_** Enter the customer's bank account number.
   - **_Can Send Money:_** Turn on if you can use this account for outgoing payments.
   - **_Bank:_** Select a bank, or click the plus icon to create one.
   - **_Account Holder:_** Select the customer.

<ImagePopup src="/images1/invoices/customer_bank.png" alt="New Bank Account modal on the customer record" />

::: tip
Add more than one bank account to define different payment channels for the same customer.
:::

## See also

- [Create an invoice](./create-invoice.md)
- [Register a payment](./register-payment.md)
- [Payment terms](../configuration/payment-terms.md)
- [Taxes](../configuration/taxes.md)
- [Bank accounts](../configuration/bank-accounts.md)
