# Vendor

The **Vendors** module in AureusERP enables efficient management of your suppliers by storing critical business, contact, and financial information. Vendor creation follows a structure similar to customer creation, with dedicated fields tailored for vendor-specific operations.

## Vendor Creation

### Steps to Create a Vendor

1.  Navigate to **`Invoices → Vendors → Vendors`**.

    ![Create Vendor](../../../images1/invoices/vendor_create.png)

2.  Fill out the form with the following details:

    ### General Section

    - **_Individual or Company:_** Identify whether the vendor is a person or a registered business. If a company is selected, the system assumes this is the primary organization, and the "Company" field becomes irrelevant.
    - **_Name:_** The official name of the vendor or contact person.
    - **_Company:_** Link this vendor to an existing company record in your system. Useful if the contact is part of a larger business group.
    - **_Tax ID:_** The government-issued tax identification number. Essential for regulatory compliance and tax reporting.
    - **_Job Title:_** Specifies the role of the individual in the vendor's organization.
    - **_Phone / Mobile:_** Primary phone numbers for contacting the vendor.
    - **_Email:_** Official email used for business communication and invoice exchange.
    - **_Website:_** Vendor's web address, used for quick reference and validation.
    - **_Title:_** Honorific or formal prefix (e.g., Mr., Ms., Dr.) for polite communication.
    - **_Tags:_** Keywords or labels used to categorize the vendor for quick searching or reporting.
    - **_Address:_** Complete address of the vendor including street, city, postal code, state, and country.

    ![Create Customer](../../../images1/invoices/vendor_create_1.png)

    ### Sales and Purchase Section

    - **Sales**

      - **_Sales Person:_** Assigns an internal team member who manages the relationship with this vendor.
      - **_Payment Terms:_** Specifies how soon the vendor expects to receive payment (e.g., immediately, after 30 days).
      - **_Payment Method:_** Defines the preferred method for the vendor to receive payments (e.g., bank transfer, cheque, cash).

    - **Purchase**

      - **_Payment Terms:_** Sets default payment deadlines for bills issued by the vendor.
      - **_Payment Method:_** Indicates how your organization intends to pay this vendor regularly.

    ![Create Vendor](../../../images1/invoices/customer_create_purchase.png)

    - **Fiscal Information**

      - **_Fiscal Position:_** Automatically maps taxes and accounts based on the vendor’s location, tax profile, or business rules. This simplifies tax computation and posting during transactions.

    - **Others**

      - **_Company ID:_** Internal identifier for the vendor, useful for linking within systems or importing/exporting data.
      - **_Reference:_** External or custom identifier for the vendor used for tracking or syncing with other systems.
      - **_Industry:_** Categorizes the vendor based on the market or sector they operate in. Useful for analytics and reporting.

    ![Create Customer](../../../images1/invoices/customer_create_others.png)

    ### Invoicing Section

    - **Customer Invoices**

      - **_Invoice Sending Method:_** Determines how invoices are exchanged—via download, email, or postal mail.
      - **_eInvoice Format:_** Specifies the format of electronic invoices (if your country mandates or supports e-invoicing).

    - **Automation**

      - **_Auto Post Bills:_** Controls whether the system should automatically post bills. Options:
        - **_Always:_** Bills from this vendor are automatically validated and posted.
        - **_Ask After 3 Validations Without Edit:_** Automatically posts if no changes are made after three validations.
        - **_Never:_** Requires manual validation and posting.
      - **_Ignore Abnormal Invoice Amount:_** Allows the system to skip warning prompts for unusually large or small invoice totals from this vendor.
      - **_Ignore Abnormal Invoice Date:_** Lets the system bypass alerts when invoice dates appear irregular (e.g., far in the past or future).

    ![Create Vendor](../../../images1/invoices/customer_create_invoicing.png)

## After Vendor Creation

Clicking **Create** saves the vendor record and redirects you to the **View Partner** page.This page provides a centralized overview of the customer's information and offers tools to manage contacts, addresses, and bank accounts.

![Create Customer](../../../images1/invoices/vendor_create_view.png)

### Edit Partner

Update the vendor’s personal, company, or fiscal details by clicking the Edit Partner button. Ideal for making corrections or updating records over time.

### Contacts

- Click on the **_Contacts_** tab to open the **Manage Contacts** page.
- Use the **_Add Contact_** button to launch a modal form.
- This form replicates the vendor creation format, allowing you to:
  - Add multiple points of contact for a vendor.
  - Capture details like name, email, phone, title, etc.

![Create Vendor](../../../images1/invoices/vendor_create_contact.png)

> 📌 **_Use Case:_** Helpful for organizations with multiple contact persons.

### Address

- Click the **_Address_** tab to navigate to the **Manage Address** page.
- Click **_Add Address_** to open a modal form with:
  - **_Toggles:_** Define the type of address — Permanent, Present, Invoice, Delivery, or Other.
  - **_Fields:_** Name, Email, Phone, Mobile, and full Address Details (Street, City, Zip Code, State, Country)

![Create Vendor](../../../images1/invoices/vendor_create_address.png)

### Bank Accounts

- Navigate to the **Bank Account** section to manage financial details.
- Click **New Bank Account** to open a modal form with the following fields:

  - **_Account Number:_** Unique identifier of the vendor’s bank account.
  - **_Can Send Money:_** Enable if this account can be used for outbound payments.
  - **_Bank:_** Choose from existing banks or click ➕ to create a new one.
  - **_Account Holder:_** Select the relevant vendor from the dropdown.

![Create Vendor](../../../images1/invoices/vendor_create_bank.png)

> 📌 **_Use Case:_** Manage multiple financial accounts for the vendor, control access, and define payment channels.

## Summary
