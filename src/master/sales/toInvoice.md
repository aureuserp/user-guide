# Order To Invoice & Order to Upsell

In **AureusERP**, the **Sales** module provides two key flows after a sales order is confirmed:

- **Order to Invoice** – for managing invoicing post-delivery
- **Order to Upsell** – for managing scenarios where more products are delivered than originally ordered (e.g., additional quantities)

This guide explains how each of these flows works in AureusERP.

## Order to Invoice

### 1. Quotation Creation

- Navigate to: **`Sales → Orders → Quotations`**
- Users create a **quotation** with product details, pricing, and terms.
- This is a draft offer and not a confirmed sale.

### 2. Quotation Confirmation

- When a quotation is confirmed:
  - It becomes a **Sales Order**.
  - A **Delivery Order** is auto-created.
- Path to view Sales Order: **Sales → Orders**

### 3. Delivery Validation

- Navigate to: **Inventory → Delivery Orders**
- Locate the delivery related to the sales order.
- Click **Validate** once the goods are dispatched.

> ⚠️ Note: In AureusERP, there is **no manual option** to create an invoice from the sales order.

### 4. Automatic Invoice Generation

- After delivery validation:
  - The system **automatically generates a customer invoice**.
  - This invoice is found under **Sales → To Invoice** or **Invoicing → Customer Invoices**.
  - The invoice is initially in **Draft** state.

### 5. Invoice Processing

- Users open the draft invoice and click **Validate** to post it.
- Upon receiving payment, click **Register Payment** to mark it as **Paid**.

## Order to Upsell

The **Order to Upsell** flow is used when **more quantity is delivered than was originally ordered**. This might happen due to customer requests or manual changes in delivery.

### When Does It Happen?

- During delivery, the quantity delivered is **increased** beyond the ordered quantity.
- AureusERP detects this and flags the order for **upselling**.

### Example:

- Sales Order: 2 units of Product A
- Delivery: 3 units of Product A
- The extra 1 unit is treated as an upsell

### Upsell Workflow

1. **Overdelivery on Delivery Order**

   - Navigate to: **Inventory → Delivery Orders**
   - Increase the quantity delivered beyond what was ordered.
   - Validate the delivery.

2. **System Flags Order to Upsell**

   - The system recognizes the overdelivery and creates a **new invoiceable line** for the extra quantity.
   - The order is added to: **Sales → Orders → To Upsell**

3. **Manage Upsell**

   - Navigate to **Sales → Orders → To Upsell**
   - Open the order.
   - Review and confirm if the additional quantities should be invoiced.

4. **Invoice Generation**
   - Upon approval or confirmation, the system generates an invoice for the **upsold quantity**.
   - The invoice appears in **Sales → To Invoice** or **Invoicing → Customer Invoices**

## Notes

- **Invoice generation is fully automated** in AureusERP and tightly coupled with the delivery validation process.
- **Upsell detection** ensures that all overdelivered items are accounted for and invoiced properly.

---
