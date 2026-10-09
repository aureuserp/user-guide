# Manage customers

A customer is a person or company you sell to. Create the customer once, then pick them on every quotation. A customer record also holds their contacts, addresses and bank accounts.

> **In simple words:** The customer record is the address book entry for the people you sell to.

## Overview

Open `Sales → Orders → Customers`. The list shows the name, email, phone, account type, job title and industry of each customer.

Use the tabs above the list:

- **_Default:_** All customers.
- **_Individuals:_** Customers who are people.
- **_Companies:_** Customers who are businesses.
- **_Archived:_** Deleted customers.

Use **Group by** to group by **Account Type**, **Parent**, **Title**, **Job Title** or **Industry**. See [Search, filter and group records](../../getting-started/search-filter-group.md).

Each row has **View**, **Edit** and **Delete** actions.

## Create a customer

1. Go to `Sales → Orders → Customers`.
2. Click **Create Customer**.

<ImagePopup src="/images1/sales/sale_customer_navigation.png" alt="Customers list with the Orders menu, Customers page and Create Customer button marked" />

3. Fill in the form.

### General

- **_Individual or Company:_** Choose the type of customer. For **Company**, the **Company** field is hidden.
- **_Name:_** The full name of the person or company.
- **_Company:_** The company the person works for. Choose one or create it.
- **_Tax ID:_** The tax identification number.
- **_Job Title:_** The role of the person.
- **_Phone:_** The main phone number.
- **_Mobile:_** The mobile number.
- **_Email:_** The email address. Quotations are sent here.
- **_Website:_** The website of the customer.
- **_Title:_** A form of address, such as Mr or Dr.
- **_Tags:_** Labels to group customers.
- **_Address:_** Street, city, zip code, state and country.

<ImagePopup src="/images1/sales/customer_create_general.png" alt="Create Customer page, General section filled in" />

### Sales and Purchase

- **Sales**

  - **_Sales Person:_** The user in charge of this customer.
  - **_Payment Terms:_** When the customer must pay after an invoice.
  - **_Payment Method:_** How the customer prefers to pay.

- **Purchase**

  - **_Payment Terms:_** When you pay this customer, if they are also a vendor.
  - **_Payment Method:_** How you pay this customer.

- **Fiscal Information**

  - **_Fiscal Position:_** The tax rules that apply to this customer.

- **Others**

  - **_Company ID:_** Your internal code for the customer.
  - **_Reference:_** Another code, such as a customer number.
  - **_Industry:_** The business sector.

### Invoicing

- **Customer Invoices**

  - **_Invoice Sending Method:_** Choose **Download**, **Email** or **Post**.
  - **_eInvoice Format:_** The electronic invoice format to use.

- **Automation**

  - **_Auto Post Bills:_** Choose **Always**, **Ask after 3 validations without edit** or **Never**.
  - **_Ignore Abnormal Invoice Amount:_** Skips the warning for unusual invoice amounts.
  - **_Ignore Abnormal Invoice Date:_** Skips the warning for unusual invoice dates.

4. Click **Create**. Click **Create & create another** to add more, or **Cancel** to leave.

::: tip
You can also create a customer without leaving a quotation. Click the plus icon next to **Customer**.
:::

## After you create a customer

Aureus opens the customer page. Use **Edit** to change the record. The page has tabs for contacts, addresses and bank accounts.

### Contacts

Add the people you deal with at a company.

1. Open the **Contacts** tab.
2. Click **Add Contact**.
3. Fill in the form. It has the same fields as a new customer.
4. Save the contact.

<ImagePopup src="/images1/sales/customer_contacts.png" alt="Create Partner window opened from the Add Contact button" />

For more on contact fields, see [Contacts](../../getting-started/contacts/contacts.md).

### Address

1. Open the **Address** tab.
2. Click **Add Address**.
3. Choose the address type: **Permanent**, **Present**, **Invoice**, **Delivery** or **Other**.
4. Enter the **Name**, **Email**, **Phone**, **Mobile** and the full address.
5. Save the address.

### Bank accounts

1. Open the **Bank Account** tab.
2. Click **New Bank Account**.
3. Fill in the form:

   - **_Account Number:_** The bank account number.
   - **_Can Send Money:_** Turn on if you can pay into this account.
   - **_Bank:_** Choose a bank or create one with the plus icon.
   - **_Account Holder:_** The customer the account belongs to.

4. Save the account.

## See also

- [Create a quotation](./create-quotation.md)
- [Contacts](../../getting-started/contacts/contacts.md)
- [Tags](../configuration/tags.md)
