# Purchase Agreements

The **Purchase Agreements** module in the **Purchases** plugin of **AureusERP** allows procurement teams to create long-term purchasing arrangements with vendors. These agreements help streamline bulk purchases, recurring orders, and negotiated pricing.

## Creating a Purchase Agreement

### Steps to Create a Purchase Agreement

1. Navigate to **`Purchase → Orders → Purchase Agreements → New Purchase Agreement`**

   ![Create Product](../../../images/create_product.png)

2. Fill out the form with the following fields:

   ### General Information Section

   - **Vendor:** Select the supplier from whom goods or services will be purchased.
   - **Valid From:** Start date of the agreement.
   - **Valid Until:** Expiry date of the agreement.
   - **Buyer:** Internal user responsible for this agreement.
   - **Reference:** Internal or vendor-specific reference for tracking the agreement.
   - **Agreement Type\*:**

     - **Blanket Orders:** Used when committing to buy specific quantities over a period.
     - **Purchase Template:** Used for templated orders with predefined products.

     > 🔹 _If `Purchase Template` is selected, `Valid From` and `Valid Until` fields are hidden as they do not apply._

   - **Company:** Select the company issuing the agreement (useful in multi-company setups).
   - **Currency:** Choose the currency in which the agreement is defined (e.g., USD, INR).

## Product Section

This section allows you to list items included in the agreement:

- **Product\*:** Choose the product from the product catalog.
- **Quantity\*:** Enter the quantity covered under this agreement.
- **Unit:** Select the unit of measure such as **Dozens**, **Units**, etc.
- **Unit Price\*:** Enter the agreed-upon unit price with the vendor.

> 🔹 _You can add multiple products to the agreement as needed._

## After Creating a Purchase Agreement

Upon clicking **Create**, the system redirects to the **Edit Purchase Agreement** page. The agreement will be in **Draft** status.

- **Confirm:**

  - Finalizes the agreement.
  - Status changes from **Draft** to **Confirmed and Posted**.
  - Fields become **read-only**.
  - The **Confirm** button changes to **Close**.

- **Close:** Marks the agreement as completed or no longer in use.
- **Cancel:** Voids the agreement.
- **Print:** Generates a print-friendly version of the agreement.
- **Delete:** Permanently removes the agreement.

## Use Case

Purchase agreements are useful for:

- Locking in prices with vendors for a fixed period.
- Reducing repetitive tasks by reusing templates.
- Managing large-scale or long-term purchases.
- Maintaining a record of vendor commitments and terms.

This completes the **Purchase Agreement** creation and management process in the **Purchases** plugin of **AureusERP**.
