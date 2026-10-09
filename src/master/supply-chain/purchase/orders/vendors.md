# Vendor

The **Vendor** module in the **Purchases** plugin of **AureusERP** is designed to manage supplier details and streamline the procurement process. Vendors are businesses or individuals from whom your company purchases products or services. Accurate vendor records are critical for managing orders, payments, and supply chain efficiency.

## Vendor Creation

### Steps to Create a Vendor

1.  Navigate to **`Purchases → Orders → Vendors → New Vendor`** as shown in the below image.

    <ImagePopup src="/images1/purchases/vendor_create.png" alt="Create Vendor" />

2.  Fill out the form with the following details:

    ### General Section

    - **_Individual or Company:_** Choose the vendor type. If "Company" is selected, the **Company** field is hidden to prevent duplication.
    - **_Name:_** Name of the contact person or vendor.
    - **_Company:_** The associated company (optional if type is company).
    - **_Tax ID:_** Enter the vendor's tax identification number.
    - **_Job Title:_** Position of the contact person.
    - **_Phone / Mobile:_** Vendor contact numbers.
    - **_Email:_** Primary contact email.
    - **_Website:_** Vendor website.
    - **_Title:_** Add titles (Mr., Ms., etc.).
    - **_Tags:_** Tags for classification.
    - **_Address:_** Include full address: street, city, state, ZIP, and country.

    <ImagePopup src="/images1/purchases/vendor_create_1.png" alt="Create Vendor" />

    ### Purchase Section

    - **_Payment Terms:_** Defines when the vendor expects payment (e.g., Immediate, Net 30).
    - **_Payment Method:_** Preferred method of payment (e.g., bank transfer, cheque).

    ### Fiscal Information

    - **_Fiscal Position:_** Select appropriate tax/accounting rules for this vendor.

    ### Other Information

    - **_Company ID:_** Internal identifier for the vendor.
    - **_Reference:_** External identifier used for syncing.
    - **_Industry:_** Business sector of the vendor.

    <ImagePopup src="/images1/purchases/vendor_create_others.png" alt="Create Vendor" />

    ### Invoicing Section

    - **_Invoice Sending Method:_** Choose between download, email, or post.
    - **_eInvoice Format:_** If applicable, select the electronic invoice format.

      - **Automation Subsection**

        - **_Auto Post Bills:_** Controls whether the system should automatically post bills.
          - _Always:_ Bills from this vendor are automatically validated and posted.
          - _Ask After 3 Validations Without Edit:_ Automatically posts if no changes are made after three validations.
          - _Never:_ Requires manual validation and posting.
        - **_Ignore Abnormal Invoice Amount:_** Skip warnings for unusually large or small invoice totals.
        - **_Ignore Abnormal Invoice Date:_** Bypass alerts for irregular invoice dates.

      <ImagePopup src="/images1/purchases/vendor_create_invoicing.png" alt="Create Vendor" />

3.  Click **_Create_** to finalize.

## Post-Creation Vendor Management

After creating a vendor, you are redirected to the **View Vendor** page where you can manage various aspects of the vendor profile:

<ImagePopup src="/images1/purchases/vendor_view.png" alt="View Vendor Page" />

- **_Edit Vendor:_** Modify vendor details such as contact info, fiscal data, etc.
- **_Contacts:_**
  - Navigate to the **_Contacts_** tab.
  - Click **_Add Contact_** to add additional contact persons with fields like name, email, phone, and title.
  - _Use Case:_ Helpful when vendors have multiple representatives.
    <ImagePopup src="/images1/purchases/vendor_contacts.png" alt="Vendor Contacts" />
- **_Address:_**
  - Go to the **_Address_** tab.
  - Click **_Add Address_** to define types like Permanent, Invoice, Delivery, etc., and fill in complete address details.
    <ImagePopup src="/images1/purchases/vendor_address.png" alt="Vendor Address" />
- **_Bank Accounts:_**
  - Click **_New Bank Account_** to add banking information.
    - **_Account Number:_** Vendor’s bank account.
    - **_Can Send Money:_** Enable for payment-enabled accounts.
    - **_Bank:_** Choose from existing or create new.
    - **_Account Holder:_** Select the vendor’s name.
  - _Use Case:_ Manage multiple financial accounts and define payment channels.
    <ImagePopup src="/images1/purchases/vendor_bank_accounts.png" alt="Vendor Bank Accounts" />
- **_Invoices:_** View all invoices linked to this vendor.
- **_Purchases:_** Track all purchase orders associated with the vendor.

## Use Case & Purpose

- _Purpose:_ Maintain comprehensive records for every supplier to ensure consistent communication, accurate billing, and timely payments.
- _Use Case:_ When onboarding a new supplier, create a vendor profile to begin issuing purchase orders, managing invoices, and processing payments efficiently.

## Summary

With proper vendor management, **AureusERP** helps your business build strong supplier relationships, track procurement, and simplify your accounts payable process.
