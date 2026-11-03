# Activity analysis

Activity analysis lists the activities your team has finished on leads and opportunities. You use it to see who did what and when, which activity types your team uses most, and how the work is spread across salespeople and teams.

> **In simple words:** It is a log of finished follow-ups, with a count you can group and chart.

Open `CRM → Reporting → Activities`. The page title is **Activities Analysis**.

## The report page

<!-- TODO-SCREENSHOT: /images1/crm/activity-analysis-list.png | Activity analysis list on the My Activities tab with finished activities -->

The page has two views: **List** and **Graph**.

### Views (tabs)

- **_My Activities:_** Activities that you finished or that were assigned to you. This tab opens first.
- **_Leads:_** Activities done on leads.
- **_Opportunities:_** Activities done on opportunities.
- **_This Month:_** Activities finished since the first day of this month.

The **Default** tab shows all activities.

### Default filter

The report starts with the rule **Completion Date is after** one year ago. Edit or remove it to see older activities.

### Columns

**Done On**, **Activity Type**, **Summary**, **Lead / Opportunity**, **Type**, **Assigned To**, **Done By**, **Salesperson** and **Sales Team**. Use the column toggle to add **Stage** and **Due Date**. The last column shows the **Count**.

### Search, filter, group and export

- Type in the search box to search by summary or by lead name.
- Use the **Salespeople** and **Sales Teams** filters.
- Use the filter builder for rules on **Activity Type**, **Assigned To**, **Done By**, **Type** and **Completion Date**.
- Click a row to open the lead or opportunity.
- Select rows and export them.

## Group by

The options are:

- **Activity Type**, **Type**
- **Assigned To**, **Done By**
- **Completion Date**, **Activity Creation Date** (grouped by month)
- **Salesperson**, **Sales Team**, **Stage**, **Company**
- **Expected Closing**, **Closed Date** (taken from the lead or opportunity, grouped by month)

**Type** here means lead or opportunity.

## Measure

This report has one measure: **Count**. It is the number of finished activities in the group.

## The Graph view

<!-- TODO-SCREENSHOT: /images1/crm/activity-analysis-graph.png | Activity analysis graph, Count by Completion Date, split by Activity Type -->

1. Click **Graph** in the view switch.
2. Keep **Count** as the measure.
3. Choose **Group by**. The default is **Completion Date**, so each bar is one month.
4. Choose **Split by**. The default is **Activity Type**, so each bar shows calls, emails and so on in colours.

## Read the report

**Example:** Your team wants to know who calls customers.

1. Open the **Opportunities** tab.
2. Group by **Done By**. Each person shows their count.
3. In the graph, split by **Activity Type**. You see how many calls, emails and meetings each month held.

If the list says **No Activities Analysis**, no one has finished an activity in the period yet. Widen the **Completion Date** rule or finish an activity first.

## Behind the scenes

- A row is added when an activity on a lead or opportunity is marked done. Open activities do not appear here.
- Each row keeps the salesperson, team and stage that the record had when the activity was done.
- **Assigned To** is who the activity was planned for. **Done By** is who finished it. They can differ.
- To schedule activities, see [Schedule activities](../pipeline/schedule-activities.md).

## See also

- [Schedule activities](../pipeline/schedule-activities.md)
- [Activities](../../../getting-started/activities.md)
- [Reporting overview](./index.md)
