# CRM configuration

Configuration holds the lists and rules that shape your sales process. You set up stages, tags, lost reasons, recurring plans and partner levels once. Your team then picks from them on every lead and opportunity.

> **In simple words:** Configuration is where you define the choices your team sees in the CRM.

Open `CRM → Configuration`. The left menu has four groups.

<!-- TODO-SCREENSHOT: /images1/crm/configuration-menu.png | CRM Configuration menu showing Members, Lead Generation, Pipeline and Activities groups -->

## What to set up and in which order

Start with the switches, then build the pipeline, then the helper lists.

```text
Settings ──> Stages ──> Tags and Lost reasons ──> Recurring plans and Levels ──> Teams
```

1. **Settings:** Decide which features you use. They reveal menus. See [CRM settings](./settings.md).
2. **Stages:** Build the columns of your pipeline board.
3. **Tags and Lost reasons:** Add the labels and the loss answers your team will pick.
4. **Recurring plans and Levels:** Add them if you sell subscriptions or rank partners.
5. **Teams:** Group your salespeople.

## Menu map

| Group | Entry | Where it is documented |
|---|---|---|
| Members | Sales Teams | [Manage sales teams](../pipeline/manage-sales-teams.md) |
| Members | Recurring Plans | [Recurring plans](./recurring-plans.md) |
| Members | Levels | [Partner levels](./partner-levels.md) |
| Lead Generation | Visitors to Leads Rules | [Lead generation](../acquire-leads/lead-generation.md) |
| Pipeline | Stages | [Stages](./stages.md) |
| Pipeline | Tags | [Tags](./tags.md) |
| Pipeline | Lost Reasons | [Lost reasons](./lost-reasons.md) |
| Activities | Activity Types | [Activities](../../../getting-started/activities.md#activity-types) |
| Activities | Activity Plans | [Activities](../../../getting-started/activities.md#schedule-from-an-activity-plan) |

**Recurring Plans** shows only when **Recurring Revenue Plans** is on in the settings.

## Pages in this group

| Page | Path | What it helps you do |
|---|---|---|
| [CRM settings](./settings.md) | `CRM → Settings → Manage CRM` | Turn features on or off and set automatic lead assignment. |
| [Stages](./stages.md) | `Configuration → Pipeline → Stages` | Define the steps of your pipeline. |
| [Tags](./tags.md) | `Configuration → Pipeline → Tags` | Label leads and opportunities with colours. |
| [Lost reasons](./lost-reasons.md) | `Configuration → Pipeline → Lost Reasons` | Record why deals are lost. |
| [Recurring plans](./recurring-plans.md) | `Configuration → Members → Recurring Plans` | Set the periods for recurring revenue. |
| [Partner levels](./partner-levels.md) | `Configuration → Members → Levels` | Rank partners and give each rank a weight. |

## Common behaviour

All the small lists work the same way.

- A **New ...** button in the page header opens a short form.
- **Edit** changes a row. A notice confirms the change.
- Tags and stages are deleted for good. Lost reasons, recurring plans and levels go to an **Archived** tab first, and you can restore them.
- A stage that still holds records cannot be deleted.
- You can export rows with the bulk action.

## Behind the scenes

- These lists feed the forms and the reports. A stage, a tag or a lost reason you add here appears at once on the forms.
- Changing a name changes it on every record that uses it.
- Reports group by these lists. See [CRM reporting](../reporting/index.md).

## See also

- [Manage opportunities](../pipeline/manage-opportunities.md)
- [CRM reporting](../reporting/index.md)
- [Create a lead](../acquire-leads/create-lead.md)
