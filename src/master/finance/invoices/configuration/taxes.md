# Taxes

Taxes control how totals are calculated on invoices and bills. A tax group bundles related taxes, and each tax belongs to a group. Create the tax group first, then the tax.

> **In simple words:** Make a group, then add taxes that use it.

## Create a tax group

A tax group bundles several rates into one entity. This keeps combined taxes tidy on documents.

1. Go to `Invoices → Configurations → Tax Groups`.
2. Click **New Tax Groups**.

   <ImagePopup src="/images1/invoices/tax_group_create.png" alt="Tax Groups list with the New Tax Groups button" />

3. Fill in the fields.

   - **_Company:_** Select the company the group is for.
   - **_Country:_** Select the country it applies to.
   - **_Name\*:_** Enter the tax group name.
   - **_Preceding Subtotal:_** Enter the reference value shown before the tax calculation.

   <ImagePopup src="/images1/invoices/tax_group_create_1.png" alt="Tax group form with company, country and name" />

4. Save the group.

## Create a tax

1. Go to `Invoices → Configurations → Tax`.
2. Click **New Tax**.

   <ImagePopup src="/images1/invoices/tax_create.png" alt="Tax list with the New Tax button" />

### General fields

- **_Name:_** Enter a label, such as Tax 15%.
- **_Tax Type\*:_** Choose **Sale**, **Purchase** or **None**.
- **_Tax Computation\*:_** Choose **Percent**, **Fixed**, **Group**, **Division** or **Custom Formula**.
- **_Tax Scope:_** Set the scope, such as goods.
- **_Status:_** Enable or disable the tax.

<ImagePopup src="/images1/invoices/tax_create_1.png" alt="General fields of the tax form" />

### Advanced options

- **_Invoice Label:_** Enter the name shown on invoices.
- **_Tax Group:_** Select a group, or create one.
- **_Country:_** Select the country it applies to.
- **_Included in Price:_** Choose **Default**, **Included** or **Excluded**.
- **_Affect Base of Subsequent Taxes:_** Toggle on to change the base of later taxes.
- **_Base Affected by Previous Taxes:_** Toggle on to let earlier taxes change this base.
- **_Description:_** Add an internal note.
- **_Legal Notes:_** Add regulatory details.

<ImagePopup src="/images1/invoices/tax_create_2.png" alt="Advanced options of the tax form" />

3. Save the tax.

::: tip
Create the tax group before the tax, so you can pick it in **Tax Group**.
:::

## See also

- [Manage products](../products/manage-products.md)
- [Create an invoice](../customers/create-invoice.md)
- [Create a bill](../vendors/create-bill.md)
- [Configuration overview](./index.md)
