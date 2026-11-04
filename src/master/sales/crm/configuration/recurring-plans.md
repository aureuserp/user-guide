# Recurring plans

A recurring plan names the period that a recurring revenue covers, such as monthly or yearly. You pick a plan on an opportunity that sells a subscription or a service contract. Aureus uses the plan to work out the monthly amount.

> **In simple words:** A recurring plan says how many months one recurring payment covers.

## Settings

The **Recurring Plans** menu shows only when **Recurring Revenue Plans** is on. Go to `CRM → Settings → Manage CRM`, turn on **Recurring Revenue Plans** and click **Save changes**. See [CRM settings](./settings.md).

Open `CRM → Configuration → Members → Recurring Plans`.

## The recurring plan list

<ImagePopup src="/images1/crm/recurring-plans-list.png" alt="Recurring plans list with Monthly, Yearly, Over 3 years and Over 5 years" />

The default plans are **Monthly** (1 month), **Yearly** (12), **Over 3 years** (36) and **Over 5 years** (60).

### Views (tabs)

- **_Active:_** Plans you can pick. The badge shows how many there are.
- **_Archived:_** Plans you deleted.

### Columns

- **_Plan:_** The name of the plan.
- **_Months:_** How many months it covers.
- **_Opportunities:_** How many opportunities use the plan.

**Example:** In the dev data, **Monthly** and **Yearly** each have 8 opportunities. The two longer plans have none.

### Search, order and export

- Type in the search box to find a plan.
- Click **Plan** or **Months** to sort.
- Drag a row handle to change the order in which plans are listed on the opportunity form.
- Select rows and use the bulk actions to export, delete, restore or delete for good.

## Create a recurring plan

1. Go to `CRM → Configuration → Members → Recurring Plans`.
2. Click **New Recurring Plan**.
3. Fill in the form.
4. Click **Create**.

<ImagePopup src="/images1/crm/recurring-plans-form.png" alt="Create Recurring Plan dialog filled with Every 6 months and 6 months" />

- **_Plan name:_** The name your team sees. Required. Up to 255 characters. The hint reads `e.g. Monthly`.
- **_Number of months:_** How many months the recurring revenue covers. Required. A whole number of at least 1. It starts at 1. Monthly is 1 and Yearly is 12.

**Example:** Name `Every 6 months` and enter 6 months. A notice says **Recurring plan created**.

## Actions and statuses

| Action | Where | What it does |
|---|---|---|
| **Edit** | Active tab | Changes the name or months. A notice says **Recurring plan updated**. |
| **Delete** | Active tab | Moves the plan to **Archived**. |
| **Restore** | Archived tab | Brings the plan back. A notice says **Recurring plan restored**. |
| **Delete** (permanent) | Archived tab | Removes the plan for good. |

## Use a plan on an opportunity

On an opportunity, two fields appear when the setting is on.

- **_Recurring Revenue:_** The amount of one recurring payment. It starts at 0.
- **_Recurring Plan:_** The plan that the payment covers. It is required as soon as **Recurring Revenue** is above 0.

Monthly recurring revenue is **Recurring Revenue** divided by the plan months. A revenue of 96,000 on **Over 3 years**, which is 36 months, is about 2,666.67 a month.

On the forecast, a card shows the recurring revenue and plan, for example `+ $18,000.00 Yearly`. See [Forecast](../reporting/forecast.md).

## Behind the scenes

- An opportunity keeps a link to its plan, even if you archive the plan later.
- Editing the months of a plan changes the monthly amount on every opportunity that uses it.
- If you turn the setting off, the plans and the saved values stay. Only the menu and fields are hidden.

## See also

- [CRM settings](./settings.md)
- [Manage opportunities](../pipeline/manage-opportunities.md)
- [Forecast](../reporting/forecast.md)
- [CRM configuration](./index.md)
