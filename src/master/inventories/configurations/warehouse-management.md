# Warehouse Management Configuration

Warehouse Management settings help you structure your warehouse operations, define storage locations, set product movement rules, and automate warehouse workflows.

## Warehouses

A warehouse is a physical storage location where goods are received, stored, and dispatched.

**Use Case:** Create warehouses when your business has multiple storage buildings or locations. Each warehouse can have its own process flow and locations.

### Steps Create a New Warehouse

1. Naviagte to **`Inventory → Configurations → Warehouse Management → Warehouses`** as shown below:

   ![Warehouse Management Navigation](/images1/inventory/navigation-warehouse-management.png)

2. Fill the following fields:

   ### General Information

   - **_Name:_** The full name of the warehouse (e.g., Central Warehouse)
   - **_Short Name:_** Short identifier for the warehouse (e.g., CW)
   - **_Company:_** Company owning this warehouse (useful in multi-company setups)
   - **_Address:_** Physical location address of the warehouse

   ![Create Warehouse](/images1/inventory/warehouse_general.png)

   ### Shipment Settings

   These define how products move in and out of the warehouse.

   #### Incoming Shipments

   - **_One Step – Receive & Store:_** Goods go directly to stock in one step
   - **_Two Steps – Receive → Store:_** Goods received at a receiving zone, then stored
   - **_Three Steps – Receive → Quality Control → Store:_** Goods received, quality-checked, then stored

   #### Outgoing Shipments

   - **_One Step – Deliver:_** Deliver goods in a single step
   - **_Two Steps – Pick → Deliver_** Pick goods first, then deliver
   - **_Three Steps – Pick → Pack → Deliver:_** Pick, then pack, then deliver in 3 steps

   ![Create Warehouse](/images1/inventory/warehouse_shipment.png)

   > **Automatic Configuration:**

   > Based on selected shipment flows, the system automatically creates **Locations, Operation Types, Routes, and Rules** for the warehouse.

3. Action Buttons

   - **_Create:_** Save warehouse
   - **_Create & Create Another:_** Save and add another
   - **_Cancel:_** Exit without saving

## Locations

A location represents a physical area inside a warehouse such as shelves, racks, receiving zone, or packing zone.

**Use Case:** Create locations when you need to organize warehouse space and track stock movement accurately.

> **Automatic Configuration:**
> When warehouse shipment steps are set (1,2,3 steps), default locations are auto-created.
> For example, in 3-step flow, system creates: **Stock, Input, Quality Control, Output, Packing Zone**

![Warehouse Locations](/images1/inventory/warehouse_locations.png)

### Steps to Create a New Location

1. Navigate to **`Inventory → Configurations → Warehouse Management → Locations`** as shown below:

   ![Warehouse Locations Navigation](/images1/inventory/navigation-warehouse-locations.png)

2. Fill in the following fields:

   ### General Information

   - **_Location Name:_** Name of the location (e.g., Shelf A, QC Zone)
   - **_Parent Location:_** Select if this location is inside another location (like aisle inside warehouse)
   - **_External Notes:_** Notes for warehouse team handling instructions etc.

   ### Location Settings

   - **_Location Type:_** Defines stock movement behavior
     - Vendor Location: Goods received from vendor
     - View: Logical grouping/no stock stored
     - Internal Location: Areas inside warehouse (main storage)
     - Customer Location: Location where items are shipped/sold
     - Inventory Loss: Location used to adjust stock differences
     - Production: For manufacturing WIP and finished goods
     - Transit Location: For goods in transit between warehouses
   - **_Company:_** Assign company
   - **_Is Dock Location:_** Marks as loading/unloading area

![Create Location](/images1/inventory/warehouse_location.png)

3. Action Buttons

   - **_Create:_** Save location
   - **_Create & Create Another:_** Save and add another
   - **_Cancel:_** Exit without saving

## Operation Types

An operation type controls how stock moves in the warehouse, including receiving, delivery, picking, and other movements.

**Use Case:** Create operation types when you need to customize workflows for receipts, delivery, internal transfers, or dropshipping.

> **Automatic Creation:**
> Operation types are auto-created when warehouse shipment flow is set.
> Example (3-step): Receipts, Pick, Pack, Delivery, Quality, Storage, Internal Transfer, Cross-dock

![Warehouse Operation Types](/images1/inventory/warehouse_operation_types.png)

### Steps to Create a New Operation Type

1. Navigate to **`Inventory → Configurations → Warehouse Management → Operation Types`** as shown below:

   ![Warehouse Operation Types Navigation](/images1/inventory/navigation-warehouse-operation-types.png)

2. Fill in the following fields:

   ### Basic Information

   - **_Operation Name:_** Name of the operation type
   - **_Operation Type:_** Select purpose (Receipt, Delivery, Internal, Dropship)
   - **_Company:_** Assigned company
   - **_Sequence Prefix:_** Prefix for operation number (e.g., REC-001)
   - **_Return Type:_** Defines how returns move
   - **_Warehouse:_** Select warehouse
   - **_Create Backorder:_** Handle partial delivery (Ask/Always/Never)

   ![Create Operation Type](/images1/inventory/warehouse_operation_type.png)

   ### Reservation Settings

   - **_Reservation Method:_**
     - At Confirm: Reserve stock when order is confirmed
     - Manual: User manually reserves
     - Before Scheduled Date: Auto-reserve before shipment date

   ### Additional Configuration

   - **_Lots/Serial Settings:_**

     - Create New: Create new lot/serial during operation
     - Use Existing: Use existing lot/serial numbers

   - **_Location Settings:_**
     - Source Location: Where goods come from
     - Destination Location: Where goods go

![Create Operation Type](/images1/inventory/warehouse_operation_type_settings.png)

3. Action Buttons

   - **_Create:_** Save operation type
   - **_Create & Create Another:_** Save and add another
   - **_Cancel:_** Exit without saving

## Routes

A route defines the product movement rules inside a warehouse, determining how goods travel between locations.

**Use Case:** Create routes when you need to control how products travel across locations (pick-pack-ship, cross-dock etc.)

> **Automatic Generation:**
> Routes are auto-generated based on warehouse setup.
> Example routes:

> - Receive in 3 steps
> - Deliver in 3 steps
> - Cross-dock

![Warehouse Routes](/images1/inventory/warehouse_routes.png)

### Steps to Create a Route

1. Navigate to **`Inventory → Configurations → Warehouse Management → Routes`** as shown below:

   ![Warehouse Routes Navigation](/images1/inventory/navigation-warehouse-routes.png)

2. Fill in the following fields:

   ### Basic Information

   - **_Route:_** Name of route
   - **_Company:_** Assign company

   ### Applicable On Settings

   - **_Available For:_**

     - Product Categories: Route available for product categories
     - Products: Route available for products
     - Packaging: Route available for packaging
     - Warehouses: Select warehouse to make default route

     ![Create Route](/images1/inventory/warehouse_route.png)

3. Action Buttons

   - **_Create:_** Save route
   - **_Create & Create Another:_** Save and add another
   - **_Cancel:_** Exit without saving

## Rules

A rule defines how products move within a route, automating warehouse operations and movements.

**Use Case:** Create rules when you need to automate actions like pull from supplier, push to packing, or move to QC.

> **Automatic Generation:**
> Three actions are auto-generated:

> - Pull From
> - Push To
> - Buy

![Warehouse Rules](/images1/inventory/warehouse_rules.png)

### Steps to Create a Rule

1. Navigate to **`Inventory → Configurations → Warehouse Management → Rules`** as shown below:

   ![Warehouse Rules Navigation](/images1/inventory/navigation-warehouse-rules.png)

2. Fill in the following fields:

   ### Basic Information

   - **_Name:_** Name of rule
   - **_Action:_** Select type (Pull, Push, Buy, Pull & Push)
   - **_Operation Type:_** Select operation type
   - **_Source Location:_** From where goods move
   - **_Destination Location:_** Where goods go

   ### Movement Settings

   - **_Partner Address:_** Vendor/customer address
   - **_Lead Time:_** Days required for movement
   - **_Route:_** Assign route
   - **_Company:_** Assign company

   ![Create Rule](/images1/inventory/warehouse_rule.png)

3. Action Buttons

   - **_Create:_** Save rule
   - **_Create & Create Another:_** Save and add another
   - **_Cancel:_** Exit without saving

## Storage Categories

A storage category helps define storage capacity rules per location, allowing you to manage space and weight limitations effectively.

**Use Case:** Create storage categories when you need to limit product storage by weight or quantity (e.g., shelf has 100kg capacity).

### Steps to Create a Storage Category

1. Navigate to **`Inventory → Configurations → Warehouse Management → Storage Category`** as shown below:

   ![Warehouse Storage Category Navigation](/images1/inventory/navigation-warehouse-storage-category.png)

2. Fill in the following fields:

   ### Basic Information

   - **_Name:_** Category name (e.g., Heavy Goods Zone)
   - **_Max Weight:_** Maximum allowed weight
   - **_Allow New Products:_** Storage type rules:
     - Mixed: Any products allowed
     - Empty: Only empty slots allowed
     - Same: Only same product allowed
   - **_Company:_** Assign company

   ### Additional Configuration Options

   - **_Capacity Management:_**

     - Capacity by Package: Set capacity by packaging type
     - Capacity by Product: Set capacity by product quantity
     - Locations: Link storage category to warehouse locations

     ![Create Storage Category](/images1/inventory/warehouse_storage_category.png)

3. Action Buttons

   - **_Create:_** Save storage category
   - **_Create & Create Another:_** Save and add another
   - **_Cancel:_** Exit without saving

### Summary

The **Warehouse Management** section in Inventory helps to:

- Configure warehouses & their shipment process
- Auto-generate warehouse structures (locations, operations, routes, rules)
- Create & manage custom warehouse locations
- Define stock movement rules & automation
- Set capacity & product storage categories

**In simple words:**  
You set up how your warehouse works, how products move in/out, where products are stored, and how operations are managed ensuring accurate and efficient inventory flow.
