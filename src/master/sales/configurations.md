# Configurations

The **Sales Configurations** section in **AureusERP** allows administrators to define reusable parameters that control behavior and enhance user productivity throughout the sales lifecycle. From managing activities and packaging to customizing product attributes and sales tags, this module centralizes critical setup operations.

## Activity Plans

> **Why it's used:** Define reusable plans that consist of sequenced activities assigned to sales teams or users. These can be associated with leads, opportunities, or orders.

### Activity Plan Creation

1. Navigate to **`Sales → Configuration → Activity Plans`** as shown below:

   ![Activity Plans Navigation](/images1/sales/activity_plans_navigation.png)

2. Fill in:

   - **_Name:_** Title of the plan (e.g., New Customer Onboarding).
   - **_Company:_** Select or create a company.
   - **_Status:_** Toggle to activate or deactivate the plan.

   ![Activity Plan Form](/images1/sales/activity_plan_form.png)

## Activity Types

> **Why it's used:** Configure different types of sales-related tasks or follow-ups (e.g., phone calls, meetings, or file uploads). These tasks can be chained to automate follow-up scheduling.

### Activity Type Creation

1. Navigate to **`Sales → Configuration → Activity Types`** as shown below:

   ![Activity Types Navigation](/images1/sales/activity_types_navigation.png)

2. Fill in Activity Type:

   #### General Information:

   - **_Activity Type:_** Label of the activity (e.g., Follow-Up Call).
   - **_Action:_** Choose from `None`, `Upload File`, `Default`, `Phone Call`, `Meeting`.
   - **_Default User:_** Assign to a user by default.
   - **_Summary_** Title/heading for the task.
   - **_Note:_** Additional description.

   #### Advanced Information:

   - **_Icon:_** Select an icon representing the task.
   - **_Decoration Type:_** Add a visual indicator (e.g., alert, error).

   - **Chaining Type** (only visible if action is not "Upload File"):
     - **_Suggest Next Activity:_** Recommends the next action.
     - **_Trigger Next Activity:_** Automatically assigns the next step.

   #### Status & Configuration:

   - **_Status:_** Enable or disable activity type.
   - **_Keep Done Activities:_** Retain completed activities for history.

   #### Delay Information:

   - **_Delay Count:_** Time gap between this and previous activity.
   - **_Delay Unit:_** Select from `Minutes`, `Hours`, `Days`, `Weeks`.
   - **_Delay From:_** Either from previous activity's deadline or completion.

   ![Activity Type Form](/images1/sales/activity_type_form.png)

## Product Packaging

> **Why it's used:** Define packaging standards used during product delivery and invoicing.

### Product Packaging Creation

1. Navigate to **`Sales → Configuration → Packaging → Product`** as shown below:

   ![Packaging Navigation](/images1/sales/packaging_navigation.png)

2. Create Packaging (Modal Form):

   - **_Name:_** Name of the packaging type.
   - **_Barcode:_** Optional barcode for the packaging.
   - **_Product:_** Link this packaging to a specific product.
   - **_Quantity:_** Number of items in one package.
   - **_Company:_** Applicable company.

   ![Product Packaging Form](/images1/sales/product_packaging_form.png)

## Categories

> **Why it's used:** Organize products into hierarchies for better navigation, segmentation, and pricing rules.

1. Navigate to **`Sales → Configuration → Products → Category`** as shown below:

   ![Categories Navigation](/images1/sales/categories_navigation.png)

2. Fill in Category Details:

   - **_Name:_** Category name (e.g., Electronics, Clothing).
   - **_Parent:_** Optionally assign a parent to create a subcategory.

   > Once created, the category can be edited, deleted, and have products added to it.

   ![Category Form](/images1/sales/category_form.png)

## Attributes

> **Why it's used:** Define product variation options (e.g., size, color) to support variant creation.

1. Navigate to **`Sales → Configuration → Products → Attributes`** as shown below:

   ![Attributes Navigation](/images1/sales/attributes_navigation.png)

2. Fill in Attribute Details:

   #### General Section:

   - **_Name:_** Attribute label (e.g., Size, Material).
   - **_Type:_** Choose one:
     - `Radio`
     - `Select`
     - `Color` (reveals color selector)

   #### Options Section:

   - **_Name:_** Value name (e.g., Large, Red).
   - **_Extra Price:_** Price adjustment when the option is selected.

   ![Attribute Form](/images1/sales/attribute_form.png)

## Tags

> **Why it's used:** Apply color-coded labels to sales orders for better filtering and tracking.

1. Navigate to **`Sales → Configuration → Sales Orders → Tags`** as shown below:

   ![Tags Navigation](/images1/sales/tags_navigation.png)

2. Create Sales Order Tag:

   - **_Name:_** Tag name (e.g., Urgent, Repeat Customer).
   - **_Color:_** Select a visual indicator.

   ![Sales Order Tag Form](/images1/sales/sales_order_tag_form.png)

## Summary

The **Sales Configurations** module in **AureusERP** provides a comprehensive set of tools to customize and optimize sales processes. By defining activity plans, activity types, product packaging, categories, attributes, and tags, administrators can create a tailored sales environment that enhances efficiency and user experience. These configurations enable better organization, automation, and tracking of sales activities, ultimately contributing to improved sales performance and customer satisfaction.
