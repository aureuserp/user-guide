# Configurations

The **Sales Configurations** section in **AureusERP** allows administrators to define reusable parameters that control behavior and enhance user productivity throughout the sales lifecycle. From managing activities and packaging to customizing product attributes and sales tags, this module centralizes critical setup operations.

## 📝 Activities

### Activity Plans

- **Navigation**: `Sales >> Configuration >> Activity Plans`
- **Purpose**: Define reusable plans that consist of sequenced activities assigned to sales teams or users. These can be associated with leads, opportunities, or orders.

#### Create Activity Plan (Modal Form Fields):

- **Name**: Title of the plan (e.g., New Customer Onboarding).
- **Company**: Select or create a company.
- **Status**: Toggle to activate or deactivate the plan.

### Activity Types

- **Navigation**: `Sales >> Configuration >> Activity Types`
- **Purpose**: Configure different types of sales-related tasks or follow-ups (e.g., phone calls, meetings, or file uploads). These tasks can be chained to automate follow-up scheduling.

#### General Information:

- **Activity Type**: Label of the activity (e.g., Follow-Up Call).
- **Action**: Choose from `None`, `Upload File`, `Default`, `Phone Call`, `Meeting`.
- **Default User**: Assign to a user by default.
- **Summary**: Title/heading for the task.
- **Note**: Additional description.

#### Advanced Information:

- **Icon**: Select an icon representing the task.
- **Decoration Type**: Add a visual indicator (e.g., alert, error).

- **Chaining Type** (only visible if action is not "Upload File"):
  - **Suggest Next Activity**: Recommends the next action.
  - **Trigger Next Activity**: Automatically assigns the next step.

#### Status & Configuration:

- **Status**: Enable or disable activity type.
- **Keep Done Activities**: Retain completed activities for history.

#### Delay Information:

- **Delay Count**: Time gap between this and previous activity.
- **Delay Unit\***: Select from `Minutes`, `Hours`, `Days`, `Weeks`.
- **Delay From\***: Either from previous activity's deadline or completion.

## 📦 Packaging

- **Navigation**: `Sales >> Configuration >> Packaging >> Product`
- **Purpose**: Define packaging standards used during product delivery and invoicing.

#### Create Packaging (Modal Fields):

- **Name**: Name of the packaging type.
- **Barcode**: Optional barcode for the packaging.
- **Product**: Link this packaging to a specific product.
- **Quantity**: Number of items in one package.
- **Company**: Applicable company.

## 🛒 Products

### Categories

- **Navigation**: `Sales >> Configuration >> Products >> Category`
- **Purpose**: Organize products into hierarchies for better navigation, segmentation, and pricing rules.

#### Create Category (Page Fields):

- **Name**: Category name (e.g., Electronics, Clothing).
- **Parent**: Optionally assign a parent to create a subcategory.

> Once created, the category can be edited, deleted, and have products added to it.

### Attributes

- **Navigation**: `Sales >> Configuration >> Products >> Attributes`
- **Purpose**: Define product variation options (e.g., size, color) to support variant creation.

#### General Section:

- **Name**: Attribute label (e.g., Size, Material).
- **Type**: Choose one:
  - `Radio`
  - `Select`
  - `Color` (reveals color selector)

#### Options Section:

- **Name**: Value name (e.g., Large, Red).
- **Extra Price**: Price adjustment when the option is selected.

## 📌 Sales Orders

### Tags

- **Navigation**: `Sales >> Configuration >> Sales Orders >> Tags`
- **Purpose**: Apply color-coded labels to sales orders for better filtering and tracking.

#### Create Tag (Modal Fields):

- **Name**: Tag name (e.g., Urgent, Repeat Customer).
- **Color**: Select a visual indicator.

These configurations enhance the flexibility, automation, and personalization of the **Sales** plugin in **AureusERP**, allowing teams to streamline their processes and scale operations effectively.
