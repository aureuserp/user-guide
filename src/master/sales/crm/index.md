# CRM

CRM is where you keep track of people who may buy from you. You record an enquiry, qualify it, work it as an opportunity, send a quotation and close the deal as won or lost. The whole team sees one pipeline, so everyone knows what to do next.

> **In simple words:** A lead is a possible customer. An opportunity is a deal you are working on. A won opportunity is a sale.

Open the app from the **CRM** item in the main menu. It has five areas: **Sales**, **Leads**, **Reporting**, **Configuration** and **Settings**.

## The flow of one deal

Here is one deal from start to finish. Sharma Textiles asks about **ERP implementation for textile manufacturing unit**.

```text
Enquiry arrives
      |
      v
   Lead  ----------------------------> Lost (with a reason)
      |  Convert to Opportunity
      v
Opportunity: New > Qualified > Proposition > Won
      |        |                              |
      |        +-- activities, notes, emails  |
      |                                       v
      +--> New Quotation --> Sales order --> Invoice
      |
      +--> Lost (with a reason)
```

1. **Lead.** You create a lead, or a visitor rule creates one. See [Create a lead](./acquire-leads/create-lead.md) and [Generate leads from visitors](./acquire-leads/lead-generation.md).
2. **Convert.** You check the lead and click **Convert to Opportunity**. See [Convert a lead](./acquire-leads/convert-lead.md).
3. **Work the opportunity.** You move the card across the stages and schedule follow-ups. See [Manage opportunities](./pipeline/manage-opportunities.md) and [Schedule activities](./pipeline/schedule-activities.md).
4. **Quotation.** You click **New Quotation** on the opportunity. See [Create a quotation](./pipeline/create-quotation.md).
5. **Close.** The customer agrees, so you mark the opportunity as won. If not, you mark it as lost and give a reason. See [Mark as won or lost](./pipeline/mark-won-lost.md).

A won deal continues in Sales as an order and an invoice. See [Quotations and orders](../sales/quotations-orders/index.md) and [Order to invoice](../sales/invoicing/order-to-invoice.md).

## Settings that reveal menus

Some features stay hidden until you switch them on. Open `CRM → Settings → Manage CRM` or the other settings pages to change them. See [CRM settings](./configuration/settings.md).

| Setting | Where | What it shows |
|---|---|---|
| **Lead Qualification** | `Manage CRM` | The **Leads** area and the **New Lead** button. Without it, new enquiries are created straight as opportunities. |
| **Recurring Revenue Plans** | `Manage CRM` | The **Recurring Plans** page and recurring revenue fields on opportunities. |
| **Salespeople in Multiple Teams** | `Manage CRM` | Lets one salesperson belong to more than one sales team. |
| **Automatic Lead Assignment** | `Manage CRM` | The **Assign now** button, **Assignment Rules** on each sales team, and assignment fields for team members. |
| **Visitors to Leads** | `Manage Lead Generation` | The **Visitors to Leads Rules** page. It needs the Website app to be installed. |
| Scoring options | `Manage Lead Scoring` | Which details feed the automatic probability. |

::: tip
If you cannot find **Leads** in the menu, switch on **Lead Qualification** first.
:::

## Pages in this module

| Group | What it helps you do |
|---|---|
| [Acquire leads](./acquire-leads/index.md) | Create leads, convert them to opportunities, merge duplicates and generate leads from website visitors. |
| [Pipeline](./pipeline/index.md) | Move opportunities across stages, schedule activities, send quotations and close deals. |
| [Assign and track](./assign-and-track/index.md) | Share leads between teams and salespeople, and score leads by chance of winning. |
| [Reporting](./reporting/index.md) | See forecasts, pipeline numbers, lead results and activities. |
| [Configuration](./configuration/index.md) | Set up stages, tags, lost reasons, recurring plans and partner levels. |

## Records you share with other apps

- **Customers** live in Contacts. You pick them in CRM, you do not set them up here. See [Contacts](../../getting-started/contacts/contacts.md).
- **Quotations** belong to Sales. CRM only starts them from an opportunity. See [Sales overview](../sales/index.md).
- **Messages and activities** use the shared tools described in [Chatter](../../getting-started/chatter/introduction.md) and [Activities](../../getting-started/activities.md).
- **Search, filter and group** work the same way in every list. See [Search, filter and group records](../../getting-started/search-filter-group.md).

## See also

- [Create a lead](./acquire-leads/create-lead.md)
- [Manage opportunities](./pipeline/manage-opportunities.md)
- [CRM settings](./configuration/settings.md)
- [Sales overview](../sales/index.md)
