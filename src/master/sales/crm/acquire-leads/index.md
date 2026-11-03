# Acquire leads

This group covers how a possible customer enters CRM and becomes an opportunity. You can create a lead by hand, or let rules create leads from website visitors. When a lead looks serious, you convert it to an opportunity and start working it in the pipeline.

> **In simple words:** First you collect names. Then you pick the good ones and work on them.

Leads are optional. Switch on **Lead Qualification** in `CRM → Settings → Manage CRM` to get the **Leads** area. See [CRM settings](../configuration/settings.md).

## The flow

```text
Source of enquiry                 Lead                    Opportunity
-----------------      +---------------------+      +------------------+
You type it in   ----> |  Check details,     | ---> | Appears in My    |
Website visitor  ----> |  priority, tags,    |      | Pipeline in the  |
matches a rule   ----> |  probability        |      | first stage      |
                       +---------------------+      +------------------+
                                  |
                                  +--> Lost (reason + note) --> Lost view
                                  +--> Merge with similar records
```

1. **Collect.** Create a lead yourself, or turn on visitor rules. See [Create a lead](./create-lead.md) and [Generate leads from visitors](./lead-generation.md).
2. **Check.** Review the contact details, priority and tags. Open the **Similar Leads** tab to find duplicates.
3. **Convert.** Click **Convert to Opportunity**. See [Convert a lead](./convert-lead.md).
4. **Work.** Continue in the [Pipeline](../pipeline/index.md).

## States of a lead

| State | Meaning | How it changes |
|---|---|---|
| **Open** | A lead you still need to check. It shows in **My Leads**, **Unassigned** and **All Leads**. | **Convert to Opportunity** or **Lost** |
| **Lost** | You closed it, or deleted it. It shows in the **Lost** view with the reason. | **Restore** |
| **Opportunity** | The lead was converted. It leaves the **Leads** list and joins the pipeline. | See [Pipeline](../pipeline/index.md) |

## Buttons on a lead

| Button | Open lead | Lost lead |
|---|---|---|
| **Convert to Opportunity** | Yes | - |
| **Lost** | Yes | - |
| **Send email** | Yes, if the lead has an email | - |
| **Send SMS** | Yes | - |
| **Delete** | Yes | - |
| **Restore** | - | Yes |

## Pages in this group

| Page | What it helps you do |
|---|---|
| [Create a lead](./create-lead.md) | Use the leads list and record a new enquiry with contact, sales and marketing details. |
| [Convert a lead](./convert-lead.md) | Turn leads into opportunities, merge duplicates and choose the customer. |
| [Generate leads from visitors](./lead-generation.md) | Create leads from website visits with rules. |

## See also

- [CRM overview](../index.md)
- [Lead scoring](../assign-and-track/lead-scoring.md)
- [Contacts](../../../getting-started/contacts/contacts.md)
