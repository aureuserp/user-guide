# Customers

The **Customers** module in the **Website Plugin** of **AureusERP** allows you to manage both frontend-registered and backend-created customers. Customers are essential stakeholders in the system, and their data includes personal details, addresses, contact info, and other business-related metadata.

## Customer Registration from Frontend

Customers can self-register directly from the website interface.

### Steps to Register as a Customer

1. Navigate to the **Frontend Website** and click on **Register**.
2. Fill out the required registration form fields:

   - **_Name:_** Full name of the customer.
   - **_Email Address:_** Valid email for login and communication.
   - **_Password:_** Create a secure password.
   - **_Confirm Password:_** Re-enter the password.

3. Click on **Sign Up**. The user is now logged in and the customer entry is recorded in the admin panel.

4. Log into the admin dashboard, go to **`Website → Customers`**, and verify the newly registered customer.

   ![Frontend Customer Registration](../../../images/customer_create_frontend.png)

### 📥 Admin View and Edit

From the admin panel, you can now:

- **Edit** the customer profile.
- Add additional data like avatar, contacts, addresses, and tags.

> ⚠️ Customers registered from the frontend **can log in**, while customers created from the admin **cannot log in to the frontend**.

## Creating a Customer from Admin Panel

### Steps to Create a Customer

1. Navigate to **`Website → Customers → New Customer`**

   ### General Section

   - **_Individual or Company:_** Toggle to specify if the customer is a person or a business.
   - **_Name:_** Full name or contact person.
   - **_Company:_** Select or create a company name.
   - **_Tax ID:_** Government-issued tax identification number.
   - **_Job Title:_** Professional title of the contact.
   - **_Phone / Mobile:_** Communication contact numbers.
   - **_Email:_** For system-generated communication and invoices.
   - **_Website:_** Link to their business website.
   - **_Title:_** Prefix like Mr., Ms., Dr., etc.
   - **_Tags:_** Helps group customers using labels or categories.
   - **_Address:_** Fill in the street, city, postal code, state, and country.
     > ![Create Customer](../../../images/customer_create_1.png)

   ### Sales and Purchase Section

   - **_Responsible:_** Assign an internal sales rep.
   - **_Company ID:_** Internal identifier for tracking.
   - **_Reference:_** External ID or vendor code.
   - **_Industry:_** Select the customer’s business domain.
     > ![Sales Purchase Info](../../../images/customer_create_others.png)

## After Customer Creation

Clicking **Create** redirects to the **View Partner** page.

### Edit Partner

Click on **Edit Partner** to update general or fiscal information.

### Manage Contacts

- Go to the **Contacts** tab.
- Click **Add Contact** to open a modal.
- Add additional contact persons with details like name, email, title, etc.

  ![Add Contact](../../../images/customer_create_contact.png)

> Useful for organizations with multiple representatives.

### 🏠 Manage Address

- Click the **Address** tab.
- Use **Add Address** to define:

  - **Address Types:** Permanent, Present, Invoice, Delivery, Other.
  - **Details:** Full name, email, phone, mobile, complete address.

  ![Add Address](../../../images/customer_create_address.png)

---

Managing customers in AureusERP allows your organization to handle leads, communications, and fulfillments efficiently, while also keeping customer records centralized and structured.
