# Purchase Agreements

The **Purchase Agreements** module in the **Purchases** plugin of **AureusERP** allows procurement teams to create long-term purchasing arrangements with vendors. These agreements help streamline bulk purchases, recurring orders, and negotiated pricing.

## Creating a Purchase Agreement

### Steps to Create a Purchase Agreement

1. Navigate to **`Purchase → Orders → Purchase Agreements → New Purchase Agreement`** as shown in the below image.

   ![Purchase Agreement Create](../../../images1/purchases/purchase_agreement_create.png)

2. Fill out the form with the following fields:

   ### General Information Section

   - **_Vendor:_** Select the supplier from whom goods or services will be purchased.
   - **_Valid From:_** Start date of the agreement.
   - **_Valid Until:_** Expiry date of the agreement.
   - **_Buyer:_** Internal user responsible for this agreement.
   - **_Reference:_** Internal or vendor-specific reference for tracking the agreement.
   - **_Agreement Type:_**

     - **_Blanket Orders:_** Used when committing to buy specific quantities over a period.
     - **_Purchase Template:_** Used for templated orders with predefined products.
       > 🔹 _If `Purchase Template` is selected, `Valid From` and `Valid Until` fields are hidden as they do not apply._

   - **_Company:_** Select the company issuing the agreement (useful in multi-company setups).
   - **_Currency:_** Choose the currency in which the agreement is defined (e.g., USD, INR).

   ![Purchase Agreement General Section](../../../images1/purchases/purchase_agreement_general.png)

## Product Section

This section allows you to list items included in the agreement:

- **_Product:_** Choose the product from the product catalog.
- **_Quantity:_** Enter the quantity covered under this agreement.
- **_Unit:_** Select the unit of measure such as **Dozens**, **Units**, etc.
- **_Unit Price:_** Enter the agreed-upon unit price with the vendor.

> 🔹 _You can add multiple products to the agreement as needed._

![Purchase Agreement Product Section](../../../images1/purchases/purchase_agreement_products.png)

## After Creating a Purchase Agreement

Upon clicking **_Create_**, the system redirects to the **_Edit Purchase Agreement_** page. The agreement will be in **_Draft_** status.

![Purchase Agreement Edit Page](../../../images1/purchases/purchase_agreement_edit.png)

- **_Confirm:_**

  - Finalizes the agreement.
  - Status changes from **_Draft_** to **_Confirmed and Posted_**.
  - Fields become **_read-only_**.
  - The **_Confirm_** button changes to **_Close_**.

- **_Close:_** Marks the agreement as completed or no longer in use.
- **_Cancel:_** Voids the agreement.
- **_Print:_** Generates a print-friendly version of the agreement.
- **_Delete:_** Permanently removes the agreement.

![Purchase Agreement Action Buttons](../../../images1/purchases/purchase_agreement_actions.png)

## Use Case

Purchase agreements are useful for:

- Locking in prices with vendors for a fixed period.
- Reducing repetitive tasks by reusing templates.
- Managing large-scale or long-term purchases.
- Maintaining a record of vendor commitments and terms.

## Summary

This guide detailed the process of creating and managing Purchase Agreements in the **Purchases** module of **AureusERP**. You learned how to fill out agreement details, add products, confirm agreements, and manage their lifecycle. Proper use of purchase agreements can lead to better vendor relationships and streamlined procurement processes.
