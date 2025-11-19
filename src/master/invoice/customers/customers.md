# Customer

The **Customer** module in **AureusERP** allows users to manage their clients by capturing all relevant personal, financial, and invoicing details. This guide walks you through the process of creating and managing customers.

## Customer Creation

### Steps to Create a Customer

1.  Navigate to **`Invoices → Customers → Customers → New Customer`** as shown in the below image.

    ![Create Customer](../../../images1/invoices/customer.png)

2.  Fill out the form with the following details:

    ### General Section

    - **_Individual or Company:_**
      - Choose whether the customer is an individual or a business entity.
      - If **Company** is selected, the **Company** field disappears to avoid redundancy.
    - **_Name:_** Full name of the individual or contact person.
    - **_Company:_** Select or create the associated company, if applicable.
    - **_Tax ID:_** Enter the official tax identification number for regulatory compliance.
    - **_Job Title:_** Job designation of the individual (if applicable).
    - **_Phone:_** Primary landline contact number.
    - **_Mobile:_** Mobile number for direct or urgent contact.
    - **_Email:_** Email address for communication and invoicing.
    - **_Website:_** Official website of the customer or company.
    - **_Title:_** Select or create a prefix like Mr., Ms., Dr., etc.
    - **_Tags:_** Use predefined or custom tags to categorize or label the customer.
    - **_Address:_** Enter the complete physical address including Street, City, Zip Code, State, and Country.

    ![Create Customer](../../../images1/invoices/customer_general.png)

    ### Sales and Purchase Section

    - **_Sales Subsection_**

      - **_Sales Person:_** Select the internal user responsible for this customer.
      - **_Payment Terms:_** Defines how long the customer has to pay after being invoiced (e.g., Net 30, Immediate).
      - **_Payment Method:_** Preferred method for receiving payments from this customer (e.g., bank transfer, cheque).

    - **_Purchase Subsection_**

      - **_Payment Terms:_** Sets default payment timeline when buying from this customer.
      - **_Payment Method:_** Indicates how your company intends to pay this customer if they’re also a vendor.

    ![Create Customer](../../../images1/invoices/customer_sales.png)

    - **_Fiscal Information Subsection_**

      - **_Fiscal Position:_** Determines the applicable tax and accounting rules for the customer, often based on location or legal entity type.

    - **_Others Subsection_**

      - **_Company ID:_** Internal reference code or identifier used for tracking this customer.
      - **_Reference:_** A secondary identifier such as a vendor/customer code.
      - **_Industry:_** Select the business sector the customer operates in; helpful for reporting and segmentation.

    ![Create Customer](../../../images1/invoices/customer_others.png)

    ### Invoicing Section

    - **_Customer Invoices Subsection_**

      - **_Invoice Sending Method:_** Choose how invoices will be sent—**Download**, **Email**, or **Post**.
      - **_eInvoice Format:_** Specify the electronic invoicing format used for compliance with legal or regional requirements.

    - **_Automation Subsection_**

      - **_Auto Post Bills:_** Controls whether the system should automatically post bills. Options:
        - **Always:** Automatically post bills.
        - **Ask after 3 validations without edit:** Semi-automatic mode after verification.
        - **Never:** Manual posting only.
      - **_Ignore Abnormal Invoice Amount:_** Toggles a rule to bypass validation warnings for unusually high or low invoice values.
      - **_Ignore Abnormal Invoice Date:_** Ignores validations triggered by suspicious or mismatched invoice dates.

    ![Create Customer](../../../images1/invoices/customer_invoicing.png)

## After Customer Creation

Once you click **Create**, you will be redirected to the **View Partner** page. This page provides a centralized overview of the customer's information and offers tools to manage contacts, addresses, and bank accounts.

![Create Customer](../../../images1/invoices/customer_view.png)

### Edit Partner

Update the customer’s personal, company, or fiscal details by clicking the Edit Partner button. Ideal for making corrections or updating records over time.

### Contacts

- Click on the **Contacts** tab to open the **Manage Contacts** page.
- Use the **Add Contact** button to launch a modal form.
- This form replicates the customer creation format, allowing you to:
  - Add multiple points of contact for a customer.
  - Capture details like name, email, phone, title, etc.

![Create Customer](../../../images1/invoices/customer_contacts.png)

> 📌 **_Use Case:_** Helpful for organizations with multiple contact persons.

### Address

- Click the **Address** tab to navigate to the **Manage Address** page.
- Click **Add Address** to open a modal form with:

  - **_Toggles:_** Define the type of address — Permanent, Present, Invoice, Delivery, or Other.
  - **_Fields:_** Name, Email, Phone, Mobile, and full Address Details (Street, City, Zip Code, State, Country)

![Create Customer](../../../images1/invoices/customer_address.png)

### Bank Accounts

- Navigate to the **Bank Account** section to manage financial details.
- Click **New Bank Account** to open a modal form with the following fields:

  - **_Account Number:_** Unique identifier of the customer’s bank account.
  - **_Can Send Money:_** Enable if this account can be used for outbound payments.
  - **_Bank:_** Choose from existing banks or click ➕ to create a new one.
  - **_Account Holder:_** Select the relevant customer from the dropdown.

![Create Customer](../../../images1/invoices/customer_bank.png)

> 📌 **_Use Case:_** Manage multiple financial accounts for the customer, control access, and define payment channels.

## Summary

The **Customer** module in **AureusERP** allows users to manage their clients by capturing all relevant personal, financial, and invoicing details. By following the steps outlined in this guide, users can efficiently create and manage customer records, ensuring accurate information for invoicing and communication purposes.
