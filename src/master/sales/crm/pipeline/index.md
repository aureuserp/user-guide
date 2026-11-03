# Pipeline

The pipeline is where you work every real sales chance from first contact to a closed deal. A deal is called an **opportunity**. It sits in one stage at a time, and you move it forward until the customer says yes or no. This group explains the whole process, from the board to the quotation.

> **In simple words:** An opportunity is a deal you are working on. You move it along the stages, send a quotation, and then win it or lose it.

Open `CRM → Sales → My Pipeline` to see the board. The other pages of this group sit in the same `CRM → Sales` section: **My Activities**, **My Quotations** and **Teams**.

## The flow

Here is one deal from start to finish. Sharma Textiles asks about an annual ERP licence.

```text
Lead ──> Opportunity ──> Quotation ──> Won
 (new)    (in a stage)    (offer)        │
                                         └──> Sales order
          Opportunity ──────────────> Lost (kept with a reason)
```

1. **Lead.** The enquiry arrives as a lead. See [Convert a lead](../acquire-leads/convert-lead.md).
2. **Opportunity.** You convert the lead. It becomes **Annual ERP licence - Sharma Textiles**. See [Manage opportunities](./manage-opportunities.md).
3. **Activities.** You plan a call and a demo. See [Schedule activities](./schedule-activities.md).
4. **Quotation.** You click **New Quotation** on the opportunity. See [Create a quotation](./create-quotation.md).
5. **Won or lost.** The customer agrees, so you click **Won**. If they decline, you click **Lost** and give a reason. See [Mark an opportunity won or lost](./mark-won-lost.md).
6. **Sales order.** A confirmed quotation becomes a sales order. See [Quotations and orders](../../sales/quotations-orders/index.md).

## Where a deal can be

An opportunity is always in one of three conditions.

| Condition | Meaning | How you see it |
|---|---|---|
| **Open** | The deal is in a normal stage such as **New**, **Qualified** or **Proposition**. | **Open** tab and a column on the board. |
| **Won** | The deal is in the stage marked **Is Won Stage?**. Probability is 100%. | **Won** tab. The card shows a **Won** label. |
| **Lost** | The deal was closed as lost. It keeps its lost reason and closing note. | **Lost** tab. The card shows a **Lost** label. |

Stages are set in `CRM → Configuration → Stages`. See [Stages](../configuration/stages.md).

## Buttons by condition

The header of an opportunity shows different buttons in each condition.

| Button | Open | Won | Lost |
|---|---|---|---|
| **Chatter** | Yes | Yes | Yes |
| **New Quotation** | Yes | Yes | No |
| **Won** | Yes | No | No |
| **Lost** | Yes | Yes | No |
| **Delete** | Yes | Yes | No |
| **Restore** | No | No | Yes |

::: info
**Send email** and **Send SMS** also appear on open and won records. **Send email** needs an email address on the record.
:::

## What changes behind the scenes

- **Stage.** Dragging a card to another column, or choosing a stage on the form, changes the stage.
- **Probability.** A won stage sets probability to 100%. A lost deal sets it to 0%.
- **Closed date.** The system stores the date when the deal is won or lost. Moving it out of the won stage clears the date.
- **Quotation link.** A quotation made from the opportunity is linked to it and shown on its **Quotations** tab.

## Pages in this group

| Page | What it helps you do |
|---|---|
| [Manage opportunities](./manage-opportunities.md) | Use the board and list, fill the opportunity form and work the record. |
| [Mark an opportunity won or lost](./mark-won-lost.md) | Close a deal and record why it was lost. |
| [Create a quotation](./create-quotation.md) | Send an offer from an opportunity and follow quotations. |
| [Manage sales teams](./manage-sales-teams.md) | Read team cards and set up teams and members. |
| [Schedule activities](./schedule-activities.md) | Plan calls and meetings and clear what is due. |

## See also

- [Convert a lead](../acquire-leads/convert-lead.md)
- [CRM reports](../reporting/index.md)
- [CRM settings](../configuration/settings.md)
