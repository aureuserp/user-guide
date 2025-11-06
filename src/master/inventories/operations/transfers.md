# Transfers

In the **Inventory module**, transfers represent the movement of products between different locations, warehouses, vendors, and customers.  
Transfers help you manage the flow of goods within the organization from receiving purchased products to delivering customer orders, handling internal stock movements, or processing dropshipping operations.

**Use Case:**  
Transfers ensure seamless tracking of product movement, proper stock adjustments, and transparency across all supply chain stages from procurement to sales.

## Receipts

**Definition:**  
A **Receipt** records the inbound movement of goods from a supplier or vendor to your warehouse.  
It helps you confirm that products purchased are received and updated in stock.

**Use Case:**  
Used when goods are received against a **Purchase Order**. This process ensures your warehouse accurately reflects incoming inventory.

> The data grid also displays automatically created receipts when a purchase order is confirmed.

### Steps to Create a New Receipt

1. Navigate to **`Inventory → Operations → Transfers → Receipts`**.

   ![Receipts Navigation](../../../images1/inventory/receipts_navigation.png)

2. Fill in the following details:

#### General Section

- **_Receive From:_** Select the vendor or supplier sending the goods.
- **_Operation Type:_** Preselected based on your warehouse configuration (e.g., `Primary Warehouse: Receipt`).
- **_Destination Location:_** Preselected warehouse input location (e.g., `Primary/Input`).

#### Operations Section

To add products:

- Click **Add to Moves**, then select:
  - **_Product:_** Choose the product being received.
  - **_Packaging:_** Choose the packaging type (e.g., Box, Crate, Pallet).
  - **_Demand:_** Enter the expected quantity to receive.
  - **_Unit:_** Select the unit of measure (e.g., Units, Dozens).
  - **_Picked:_** Toggle to mark the product as picked.
  - You can add multiple product lines here.

#### Additional Section

- **_Responsible:_** The user handling the receipt process.
- **_Scheduled At:_** The planned date/time of receipt.
- **_Source Document:_** Auto-linked purchase order or reference document.

3. **Action Buttons:**
   - **Create** – Save and open the receipt record.
   - **Create & Create Another** – Save and open a new blank form.
   - **Cancel** – Discard and return to list view.

### Receipt Workflow Actions

Once created, you are redirected to the **Receipt View Page**, which includes:

- **View:** View all receipt details.
- **Edit:** Modify details in draft state.
- **Moves:** Review all product moves linked to the receipt.
- **Mark as To Do:** Changes the status from **Draft → Ready**, validating stock availability.
- **Validate:** Confirms the receipt and updates inventory (status becomes **Done**). Fields become read-only.
- **Return:** Available after validation — creates a reverse receipt (delivery).
- **Cancel / Delete:** Stop or remove the receipt record.

## Deliveries

**Definition:**  
A **Delivery Order** records the outbound movement of goods from your warehouse to a customer.

**Use Case:**  
Used when fulfilling sales orders or shipping goods to customers. It ensures accurate stock deductions and transparent delivery tracking.

> The data grid also displays automatically created deliveries when a **Sales Order** is confirmed.

### Steps to Create a New Delivery

1. Navigate to **`Inventory → Operations → Transfers → Deliveries`**.

   ![Delivery Navigation](../../../images1/inventory/delivery_navigation.png)

2. Fill in the following details:

#### General Section

- **_Delivery Address:_** Select the customer receiving the goods.
- **_Operation Type:_** Preselected (e.g., `Primary Warehouse: Delivery Order`).
- **_Destination Location:_** Preselected warehouse output location (e.g., `Primary/Output`).

#### Operations Section

- Click **Add to Moves**, then select:
  - **_Product:_** Choose the product to deliver.
  - **_Packaging:_** Specify the packaging used for the shipment.
  - **_Demand:_** Enter quantity to deliver.
  - **_Unit:_** Select the unit of measure.
  - **_Picked:_** Enable to mark products picked for delivery.

#### Additional Section

- **_Responsible:_** Person managing the delivery.
- **_Shipping Policy:_** Choose whether to ship all items together or as available.
- **_Scheduled At:_** Planned delivery date.
- **_Source Document:_** Linked sales order or reference.

3. **Action Buttons:**
   - **Create** – Save and open the delivery record.
   - **Create & Create Another** – Save and create another record.
   - **Cancel** – Exit without saving.

### Delivery Workflow Actions

- **Mark as To Do:** Changes status from **Draft → Ready**, validates stock availability.
- **Validate:** Confirms delivery, reduces stock, and changes status to **Done**.
- **Return:** Creates a return (receipt) for the delivery.
- **Cancel / Delete:** Stop or remove the delivery record.

## Internal Transfers

**Definition:**  
An **Internal Transfer** represents the movement of products within your own warehouse — from one location to another.

**Use Case:**  
Used when products move between areas (e.g., from stock to packing zone or quality control). It helps maintain location-level inventory accuracy.

### Steps to Create a New Internal Transfer

1. Navigate to **`Inventory → Operations → Transfers → Internal Transfers`**.

   ![Internal Transfers Navigation](../../../images1/inventory/internal_transfer_navigation.png)

2. Fill in the following details:

#### General Section

- **_Contact:_** Internal contact or responsible person.
- **_Operation Type:_** Preselected (e.g., `Primary Warehouse: Pick`).
- **_Source Location:_** Preselected source location (e.g., `Primary/Stock`).
- **_Destination Location:_** Preselected destination (e.g., `Primary/Packing Zone`).

#### Operations Section

- **_Product:_** Product to move internally.
- **_Packaging:_** Choose packaging if applicable.
- **_Demand:_** Quantity to move.
- **_Unit:_** Unit of measure.
- **_Picked:_** Toggle to mark as picked.

#### Additional Section

- **_Responsible:_** User managing the internal movement.
- **_Shipping Policy:_** Choose transfer policy.
- **_Scheduled At:_** Date for transfer.
- **_Source Document:_** Related reference.

3. **Action Buttons:**
   - **Create**
   - **Create & Create Another**
   - **Cancel**

### Internal Transfer Workflow Actions

- **Mark as To Do:** Status changes from **Draft → Ready**, checks stock availability, and creates move records.
- **Validate:** Completes transfer, updating locations (status **Done**).
- **Return:** Reverses the movement (e.g., from packing zone back to stock).
- **Cancel / Delete:** Remove or discard the record.

## Dropships

**Definition:**  
**Dropship Transfers** record the movement of products shipped directly from the vendor to the customer without passing through your warehouse.

**Use Case:**  
Useful for direct-to-customer fulfillment, reducing warehouse handling and improving delivery time.

### Steps to Create a New Dropship

1. Navigate to **`Inventory → Operations → Transfers → Dropships`**.

   ![Dropship Navigation](../../../images1/inventory/dropship_navigation.png)

2. Fill in the following details:

#### General Section

- **_Operation Type:_** Preselected as **Dropship**.
- **_Source Location:_** Auto-selected as **Partner/Vendor**.
- **_Destination Location:_** Auto-selected as **Partner/Customer**.

#### Operations Section

- **_Product:_** Select the product being dropshipped.
- **_Packaging:_** Select packaging type.
- **_Demand:_** Quantity to deliver.
- **_Unit:_** Unit of measure.
- **_Picked:_** Enable if products are picked.

#### Additional Section

- **_Responsible:_** The user managing the dropship.
- **_Shipping Policy:_** Define delivery rule.
- **_Scheduled At:_** Planned shipping date.
- **_Source Document:_** Linked purchase or sales order.

3. **Action Buttons:**
   - **Create**
   - **Create & Create Another**
   - **Cancel**

### Dropship Workflow Actions

- **Mark as To Do:** Changes status from **Draft → Ready**, validating moves.
- **Validate:** Completes the dropship (status **Done**).
- **Return:** Reverses the dropship (customer → vendor).
- **Cancel / Delete:** Stop or remove the record.

## Summary

The **Transfers** module in Inventory provides complete control over product movements:

- **Receipts:** Record inbound goods from vendors.
- **Deliveries:** Track outbound goods to customers.
- **Internal Transfers:** Manage intra-warehouse stock movement.
- **Dropships:** Handle direct vendor-to-customer shipments.

Each transfer type supports:

- **Operation Tracking:** Monitor every stage of movement.
- **Validation Workflow:** Ensure accuracy before updating stock.
- **Returns Management:** Reverse any completed operation.

This ensures full transparency, accuracy, and efficiency in warehouse operations across all movement types.
