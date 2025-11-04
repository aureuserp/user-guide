# 📦 Inventory Configuration – Warehouse Management

Warehouse Management settings help you structure your warehouse operations, define storage locations, set product movement rules, and automate warehouse workflows.

---

## 🏭 Warehouses

A warehouse is a physical storage location where goods are received, stored, and dispatched.  
**Use Case:** Create warehouses when your business has multiple storage buildings or locations. Each warehouse can have its own process flow and locations.

### ➕ Create a New Warehouse

1. Go to **Inventory → Configurations → Warehouse Management → Warehouses**
2. Fill the following fields:

### General Information

| Field          | Meaning                                                        |
| -------------- | -------------------------------------------------------------- |
| **Name**       | The full name of the warehouse (e.g., Central Warehouse)       |
| **Short Name** | Short identifier for the warehouse (e.g., WH1)                 |
| **Company**    | Company owning this warehouse (useful in multi-company setups) |
| **Address**    | Physical location address of the warehouse                     |

### Shipment Settings

These define how products move in and out of the warehouse.

#### Incoming Shipments

| Option                                              | Meaning                                         |
| --------------------------------------------------- | ----------------------------------------------- |
| **One Step – Receive & Store**                      | Goods go directly to stock in one step          |
| **Two Steps – Receive → Store**                     | Goods received at a receiving zone, then stored |
| **Three Steps – Receive → Quality Control → Store** | Goods received, quality-checked, then stored    |

#### Outgoing Shipments

| Option                                  | Meaning                                  |
| --------------------------------------- | ---------------------------------------- |
| **One Step – Deliver**                  | Deliver goods in a single step           |
| **Two Steps – Pick → Deliver**          | Pick goods first, then deliver           |
| **Three Steps – Pick → Pack → Deliver** | Pick, then pack, then deliver in 3 steps |

> **Automatic Configuration:**  
> Based on selected shipment flows, the system automatically creates **Locations, Operation Types, Routes, and Rules** for the warehouse.

### Action Buttons

- **Create** – Save warehouse
- **Create & Create Another** – Save and add another
- **Cancel** – Exit without saving

---

## 🗂️ Locations

Locations represent physical areas inside a warehouse such as shelves, racks, receiving zone, packing zone etc.

**Use Case:** Organize warehouse space and track stock movement accurately.

> When warehouse shipment steps are set (1,2,3 steps), default locations are auto-created.  
> For example, in 3-step flow, system creates: **Stock, Input, Quality Control, Output, Packing Zone**

### ➕ Create a New Location

1. Go to **Inventory → Configurations → Warehouse Management → Locations**
2. Fill the fields:

| Field               | Meaning                                                                          |
| ------------------- | -------------------------------------------------------------------------------- |
| **Location Name**   | Name of the location (e.g., Shelf A, QC Zone)                                    |
| **Parent Location** | Select if this location is inside another location (like aisle inside warehouse) |
| **External Notes**  | Notes for warehouse team — handling instructions etc.                            |

### Settings

| Field                | Meaning                                   |
| -------------------- | ----------------------------------------- |
| **Location Type**    | Defines stock movement behavior           |
| Options              | Usage                                     |
| Vendor Location      | Goods received from vendor                |
| View                 | Logical grouping/no stock stored          |
| Internal Location    | Areas inside warehouse (main storage)     |
| Customer Location    | Location where items are shipped/sold     |
| Inventory Loss       | Location used to adjust stock differences |
| Production           | For manufacturing WIP and finished goods  |
| Transit Location     | For goods in transit between warehouses   |
| **Company**          | Assign company                            |
| **Is Dock Location** | Marks as loading/unloading area           |

### Actions

- Create
- Create & create another
- Cancel

---

## 🔁 Operation Types

Operation Types control how stock moves in the warehouse (receiving, delivery, picking etc.)

**Use Case:** Customize workflows for receipts, delivery, internal transfers, dropshipping etc.

> Auto-created when warehouse shipment flow is set.  
> Example (3-step): Receipts, Pick, Pack, Delivery, Quality, Storage, Internal Transfer, Cross-dock

### ➕ Create New Operation Type

1. Go to **Inventory → Configurations → Warehouse Management → Operation Types**

| Field                | Meaning                                               |
| -------------------- | ----------------------------------------------------- |
| **Operation Name**   | Name of the operation type                            |
| **Operation Type**   | Select purpose: Receipt, Delivery, Internal, Dropship |
| **Company**          | Assigned company                                      |
| **Sequence Prefix**  | Prefix for operation number (e.g., REC-001)           |
| **Return Type**      | Defines how returns move                              |
| **Warehouse**        | Select warehouse                                      |
| **Create Backorder** | Handle partial delivery (Ask/Always/Never)            |

### Reservation Method

| Option                | Meaning                               |
| --------------------- | ------------------------------------- |
| At Confirm            | Reserve stock when order is confirmed |
| Manual                | User manually reserves                |
| Before Scheduled Date | Auto-reserve before shipment date     |

### Lots/Serial Settings

| Toggle       | Use                                    |
| ------------ | -------------------------------------- |
| Create New   | Create new lot/serial during operation |
| Use Existing | Use existing lot/serial numbers        |

### Locations

| Field                | Meaning               |
| -------------------- | --------------------- |
| Source Location      | Where goods come from |
| Destination Location | Where goods go        |

### Actions

- Create
- Create & create another
- Cancel

---

## 🚛 Routes

Routes define product movement rules inside warehouse.  
**Use Case:** Control how products travel across locations (pick-pack-ship, cross-dock etc.)

> Auto-generated based on warehouse setup  
> Example routes:

- Receive in 3 steps
- Deliver in 3 steps
- Cross-dock

### ➕ Create a Route

1. Go to **Inventory → Configurations → Warehouse Management → Routes**

| Field       | Meaning        |
| ----------- | -------------- |
| **Route**   | Name of route  |
| **Company** | Assign company |

### Applicable On

Select where this route appears for selection:

| Toggle             | Use                                    |
| ------------------ | -------------------------------------- |
| Product Categories | Route available for product categories |
| Products           | Route available for products           |
| Packaging          | Route available for packaging          |
| Warehouses         | Select warehouse to make default route |

### Actions

- Create
- Create & create another
- Cancel

---

## ⚙️ Rules

Rules define how products move within a route.  
**Use Case:** Automate actions like pull from supplier, push to packing, move to QC etc.

> 3 actions auto-generated: **Pull From, Push To, Buy**

### ➕ Create Rule

1. Go to **Inventory → Configurations → Warehouse Management → Rules**

| Field                    | Meaning                      |
| ------------------------ | ---------------------------- |
| **Name**                 | Name of rule                 |
| **Action**               | Pull, Push, Buy, Pull & Push |
| **Operation Type**       | Select operation type        |
| **Source Location**      | From where goods move        |
| **Destination Location** | Where goods go               |

### Settings

| Field           | Meaning                    |
| --------------- | -------------------------- |
| Partner Address | Vendor/customer address    |
| Lead Time       | Days required for movement |
| Route           | Assign route               |
| Company         | Assign company             |

### Actions

- Create
- Create & create another
- Cancel

---

## 🗃️ Storage Categories

Storage categories help define storage capacity rules per location.

**Use Case:** Limit product storage by weight or quantity (e.g., shelf has 100kg capacity)

### ➕ Create Storage Category

1. Go to **Inventory → Configurations → Warehouse Management → Storage Category**

| Field                  | Meaning                                |
| ---------------------- | -------------------------------------- |
| **Name**               | Category name (e.g., Heavy Goods Zone) |
| **Max Weight**         | Maximum allowed weight                 |
| **Allow New Products** | Storage type rules                     |

| Option | Meaning                   |
| ------ | ------------------------- |
| Mixed  | Any products allowed      |
| Empty  | Only empty slots allowed  |
| Same   | Only same product allowed |

| Field       | Meaning        |
| ----------- | -------------- |
| **Company** | Assign company |

### After Create – Additional Options

| Page                | Purpose                                      |
| ------------------- | -------------------------------------------- |
| Capacity by Package | Set capacity by packaging type               |
| Capacity by Product | Set capacity by product quantity             |
| Locations           | Link storage category to warehouse locations |

---

✅ This completes **Inventory Configuration – Warehouse Management** guide.

---

Would you like to proceed to **Product Configuration**, **Operations (Receipts, Delivery, Transfers)**, or **Traceability (Lots & Serials)** next?
