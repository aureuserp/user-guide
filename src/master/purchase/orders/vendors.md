# Vendor

The **Vendor** module in the **Purchases** plugin of **AureusERP** is designed to manage supplier details and streamline the procurement process. Vendors are businesses or individuals from whom your company purchases products or services. Accurate vendor records are critical for managing orders, payments, and supply chain efficiency.

## Vendor Creation

### Steps to Create a Vendor

1.  Navigate to **Purchases >> Orders >> Vendors >> New Vendor**.

2.  Fill out the form with the following details:

    ### General Section

    - **Individual or Company:** Choose the vendor type. If "Company" is selected, the **Company** field is hidden to prevent duplication.
    - **Name:** Name of the contact person or vendor.
    - **Company:** The associated company (optional if type is company).
    - **Tax ID:** Enter the vendor's tax identification number.
    - **Job Title:** Position of the contact person.
    - **Phone / Mobile:** Vendor contact numbers.
    - **Email:** Primary contact email.
    - **Website:** Vendor website.
    - **Title:** Add titles (Mr., Ms., etc.).
    - **Tags:** Tags for classification.
    - **Address:** Include full address: street, city, state, ZIP, and country.

    ### Purchase Section

    - **Payment Terms:** Defines when the vendor expects payment (e.g., Immediate, Net 30).
    - **Payment Method:** Preferred method of payment (e.g., bank transfer, cheque).

    ### Fiscal Information

    - **Fiscal Position:** Select appropriate tax/accounting rules for this vendor.

    ### Other Information

    - **Company ID:** Internal identifier for the vendor.
    - **Reference:** External identifier used for syncing.
    - **Industry:** Business sector of the vendor.

    ### Invoicing Section

    - **Invoice Sending Method:** Choose between download, email, or post.
    - **eInvoice Format:** If applicable, select the electronic invoice format.

    - **Automation Subsection**

      - **Auto Post Bills:** Controls whether the system should automatically post bills.
        - _Always:_ Bills from this vendor are automatically validated and posted.
        - _Ask After 3 Validations Without Edit:_ Automatically posts if no changes are made after three validations.
        - _Never:_ Requires manual validation and posting.
      - **Ignore Abnormal Invoice Amount:** Skip warnings for unusually large or small invoice totals.
      - **Ignore Abnormal Invoice Date:** Bypass alerts for irregular invoice dates.

3.  Click **Create** to finalize. You will be redirected to the **View Vendor** page.

    ### View Vendor Page Tools

    - **Edit Vendor:** Modify vendor details such as contact info, fiscal data, etc.
    - **Contacts:**
      - Navigate to the **Contacts** tab.
      - Click **Add Contact** to add additional contact persons with fields like name, email, phone, and title.
      - _Use Case:_ Helpful when vendors have multiple representatives.
    - **Address:**
      - Go to the **Address** tab.
      - Click **Add Address** to define types like Permanent, Invoice, Delivery, etc., and fill in complete address details.
    - **Bank Accounts:**
      - Click **New Bank Account** to add banking information.
        - **Account Number\***: Vendor’s bank account.
        - **Can Send Money:** Enable for payment-enabled accounts.
        - **Bank\***: Choose from existing or create new.
        - **Account Holder\***: Select the vendor’s name.
      - _Use Case:_ Manage multiple financial accounts and define payment channels.
    - **Invoices:** View all invoices linked to this vendor.
    - **Purchases:** Track all purchase orders associated with the vendor.

## Use Case & Purpose

- _Purpose:_ Maintain comprehensive records for every supplier to ensure consistent communication, accurate billing, and timely payments.
- _Use Case:_ When onboarding a new supplier, create a vendor profile to begin issuing purchase orders, managing invoices, and processing payments efficiently.

---

With proper vendor management, **AureusERP** helps your business build strong supplier relationships, track procurement, and simplify your accounts payable process.
