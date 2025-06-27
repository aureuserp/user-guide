# Settings – Purchases Plugin

The **Settings** section of the **Purchases** plugin in **AureusERP** allows users to configure how purchase workflows and products are managed. These settings ensure greater control over purchase orders, product handling, and user permissions.

## Manage Orders

Navigate to **Purchase >> Settings >> Manage Orders** as shown in the below image.

![Settings](../../../images/roles.png)

This section helps you control how purchase orders behave in your organization.

### Purchase Order Approval

- **Purpose:** Enable this to **require manager approval** for purchase orders that **exceed a defined minimum amount**.
- **Use Case:** Useful for organizations that want to avoid unauthorized or high-cost purchases without oversight.
- **Field:**
  - **Minimum Amount:** Specify the amount above which approval is required.

### Lock Confirmed Orders

- **Purpose:** Automatically lock a purchase order once it is **confirmed**, preventing any further changes.
- **Use Case:** Ensures integrity and avoids accidental edits after vendor confirmation.

### Purchase Agreements

- **Purpose:** Enable management of **Blanket Orders** and **Purchase Templates**.
- **Use Case:** Useful for companies that regularly place bulk or recurring orders under agreed terms.

📝 **Tip:** After enabling your desired toggles, click **Save Changes** to apply your settings.

## Manage Products

Navigate to **Purchase >> Settings >> Manage Products** as shown in the below image.

![Settings](../../../images/roles.png)

This section defines how product variations and measurements are handled during procurement.

### Variants

- **Purpose:** Manage product variations such as **Color**, **Size**, or **Material**.
- **Use Case:** Allows for precise tracking and ordering of product variants.

### Unit of Measure

- **Purpose:** Enables buying and selling products in **different units** (e.g., pieces, boxes, dozens).
- **Use Case:** Perfect for managing bulk purchases or packaging conversions.

### Packagings

- **Purpose:** Lets you define and manage different **product packaging types**, such as boxes, packs, or containers.
- **Use Case:** Helps streamline warehouse and shipping operations by tracking product pack sizes.

📝 **Tip:** Enable all toggles for full product functionality in your purchase operations, then click **Save Changes**.

## Roles & Permissions – Purchase Plugin

After configuring the toggles, navigate to:

Navigate to **Settings >> Roles >> [Select Role] >>edit** as shown in the below image.

![Settings](../../../images/roles.png)

In the **Purchases Plugin section**, ensure proper permissions are granted to resources like:

- **Packaging**
- **Attribute**

### Available Actions for Each Resource

- **View**
- **View Any**
- **Create**
- **Update**
- **Restore**
- **Restore Any**
- **Replicate**
- **Reorder**
- **Delete**
- **Delete Any**
- **Force Delete**
- **Force Delete Any**

> **Tip:** Enabling these actions ensures your team has complete access to manage packaging and attribute-related data in the Purchases module.

## Select All Shortcut

- **Purpose:** Quickly grant **full access** to all pages and resources.
- **How:** Use the **Select All** toggle at the top of the permissions list.
- **Benefit:** Saves time during setup, especially for admin or manager roles.

## Summary

Proper configuration of **Manage Orders** and **Manage Products** in the Purchases plugin ensures a smooth procurement process. Don’t forget to assign permissions for every resource involved to enable seamless access and control across your purchase workflows.
