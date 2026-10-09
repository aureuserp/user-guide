# Manage vendors

A vendor is a supplier you buy from. The vendor record stores contact, tax, payment and bank details. Bills, refunds and payments all pick the vendor from this list.

> **In simple words:** A vendor record is the supplier's profile that you reuse on every bill.

## Create a vendor

1. Go to `Invoices → Vendors → Vendors` and click **New**.

   <ImagePopup src="/images1/invoices/vendor_create.png" alt="Vendors list with the button to create a new vendor" />

2. Fill in the form sections below.

### General

**_Individual or Company:_** Choose whether the vendor is a person or a business. For a company, the **Company** field does not apply.

**_Name:_** Enter the official name of the vendor or contact person.

**_Company:_** Link the vendor to an existing company record.

**_Tax ID:_** Enter the government tax identification number.

**_Job Title:_** Enter the person's role in the vendor's organization.

**_Phone / Mobile:_** Enter the primary phone numbers.

**_Email:_** Enter the email used for business communication.

**_Website:_** Enter the vendor's web address.

**_Title:_** Select a formal prefix, for example Mr., Ms. or Dr.

**_Tags:_** Add labels to find and group vendors.

**_Address:_** Enter the street, city, postal code, state and country.

<ImagePopup src="/images1/invoices/vendor_create_1.png" alt="General section of the vendor form" />

### Sales and purchase

Under **Sales**:

**_Sales Person:_** Select the team member who manages this vendor relationship.

**_Payment Terms:_** Set how soon the vendor expects payment.

**_Payment Method:_** Set the preferred payment method, for example bank transfer or cheque.

Under **Purchase**:

**_Payment Terms:_** Set the default payment deadline for bills from this vendor.

**_Payment Method:_** Set how you usually pay this vendor.

<ImagePopup src="/images1/invoices/customer_sales.png" alt="Sales and purchase section of the vendor form" />

Under **Fiscal Information**:

**_Fiscal Position:_** Map taxes and accounts automatically from the vendor's location or tax profile.

Under **Others**:

**_Company ID:_** Enter an internal identifier for the vendor.

**_Reference:_** Enter an external identifier used to sync with other systems.

**_Industry:_** Select the vendor's sector. This helps with reporting.

<ImagePopup src="/images1/invoices/customer_create_others.png" alt="Fiscal information and other fields of the vendor form" />

### Invoicing

Under **Customer Invoices**:

**_Invoice Sending Method:_** Choose how invoices are shared: download, email or post.

**_eInvoice Format:_** Choose the electronic invoice format if your country supports it.

Under **Automation**:

**_Auto Post Bills:_** Choose when bills from this vendor post automatically.

- **_Always:_** Bills are validated and posted automatically.
- **_Ask After 3 Validations Without Edit:_** The system asks after three validations with no edits.
- **_Never:_** You validate and post bills manually.

**_Ignore Abnormal Invoice Amount:_** Skip warnings for unusually large or small totals.

**_Ignore Abnormal Invoice Date:_** Skip alerts for dates far in the past or future.

<ImagePopup src="/images1/invoices/customer_create_invoicing.png" alt="Invoicing and automation fields of the vendor form" />

3. Click **Create**.

## Actions and statuses

Clicking **Create** saves the vendor and opens the partner view. Use it to edit the vendor and manage contacts, addresses and bank accounts.

<ImagePopup src="/images1/invoices/vendor_create_view.png" alt="Vendor view page with edit button and contact, address and bank account tabs" />

### Edit the partner

Click **Edit Partner** to change personal, company or fiscal details.

### Contacts

1. Open the **Contacts** tab.
2. Click **Add Contact**.
3. Fill in name, email, phone, title and other details, then save.

<ImagePopup src="/images1/invoices/vendor_create_contact.png" alt="Add contact form for a vendor" />

### Addresses

1. Open the **Address** tab.
2. Click **Add Address**.
3. Pick the address type: Permanent, Present, Invoice, Delivery or Other.
4. Enter name, email, phone, mobile, street, city, zip code, state and country.

<ImagePopup src="/images1/invoices/vendor_create_address.png" alt="Add address form for a vendor" />

### Bank accounts

1. Open the bank account section.
2. Click **New Bank Account**.
3. Fill in the fields below.

**_Account Number:_** Enter the vendor's bank account number.

**_Can Send Money:_** Turn on if you can use this account for outgoing payments.

**_Bank:_** Select a bank, or use the plus icon to create one.

**_Account Holder:_** Select the vendor.

<ImagePopup src="/images1/invoices/vendor_create_bank.png" alt="New bank account form for a vendor" />

::: tip
Add several contacts and bank accounts when a vendor has more than one person or account.
:::

## See also

- [Create a bill](./create-bill.md)
- [Register a payment](./register-payment.md)
- [Bank accounts](../configuration/bank-accounts.md)
- [Payment terms](../configuration/payment-terms.md)
