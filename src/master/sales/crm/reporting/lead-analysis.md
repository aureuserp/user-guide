# Lead analysis

Lead analysis covers every lead and every opportunity, including the ones you lost. You use it to count how many records came in, see who works on them, and compare won and lost results over time.

> **In simple words:** Pipeline analysis looks at open deals. Lead analysis looks at everything, from the first lead to the final win or loss.

Open `CRM → Reporting → Leads`. The page title is **Leads Analysis**.

## The report page

<!-- TODO-SCREENSHOT: /images1/crm/lead-analysis-list.png | Lead analysis list on the Leads tab with Group by, Measure and the summary row -->

The page has two views: **List** and **Graph**.

### Views (tabs)

- **_Leads:_** Records that are still leads. This tab opens first.
- **_Opportunities:_** Records that are opportunities.
- **_Mine:_** Records where you are the salesperson.
- **_Won:_** Records in a won stage.
- **_Lost:_** Records you marked as lost.

The **Default** tab shows every record.

**Example:** The dev data shows 24 records in **Default**, 16 in **Leads**, 8 in **Opportunities**, 12 in **Mine**, 1 in **Won** and 0 in **Lost**.

### Default filter

The report starts with the rule **Created On is after** the first day of this year. Edit or remove it to look further back.

### Columns

**Name**, **Type**, **Customer**, **Stage**, **Expected Revenue**, **Probability**, **Salesperson**, **Sales Team**, **Expected Closing**, **Created On** and **Closed On**. Use the column toggle to add **Lost Reason**, **Country** and **City**. The last column shows the measure.

A summary row shows the total for the page. A second row shows the total for the whole report.

### Search, filter, group and export

- Type in the search box to find a record.
- Use the **Salespeople** and **Sales Teams** filters.
- Use the filter builder for rules on **Salesperson**, **Type**, **Expected Closing**, **Active**, **Won** and **Closed Date**.
- Click a row to open the lead or opportunity. Lost rows do not open.
- Select rows to export, delete, restore, mark as lost, merge, or send email or SMS.

## Group by

The options are:

- **Salesperson**, **Sales Team**, **Stage**, **Type**
- **City**, **Country**, **Company**
- **Lost Reason**
- **Campaign**, **Medium**, **Source**
- **Expected Closing**, **Creation Date**, **Conversion Date**, **Closed Date** (grouped by month)

**Type** is the only option that this report has and Pipeline analysis does not. It separates leads from opportunities.

## Measure

| Measure | True meaning |
|---|---|
| **Count** | How many records are in the group. This is the default. |
| **Expected Revenue** | The sum of **Expected Revenue**. Leads often have 0. |
| **Prorated Revenue** | The sum of expected revenue times probability divided by 100. |
| **Probability (avg.)** | The average **Probability**, shown as a percentage. |
| **Days to Assign** | The average days from creation to the day a salesperson was assigned. |
| **Days to Close** | The average days from creation to the closed date. |

## The Graph view

<!-- TODO-SCREENSHOT: /images1/crm/lead-analysis-graph.png | Lead analysis graph, Count by Creation Date, split by Sales Team -->

1. Click **Graph** in the view switch.
2. Choose a **Measure**. The default is **Count**.
3. Choose **Group by**. The default is **Creation Date**, so each bar is one month.
4. Choose **Split by**. The default is **Sales Team**, so each bar is stacked by team.

The title reads, for example, **Count by Creation Date**.

## Read the report

**Example:** On the **Leads** tab with the year filter, the summary row shows **Count 16** and **Expected Revenue $0.00**.

1. Set **Group by** to **Salesperson**. Each group shows how many leads each person holds.
2. Change **Measure** to **Probability (avg.)**. You see which salesperson holds the more promising leads.
3. Switch to the **Won** tab and group by **Source**. You see which source brings the deals you win.
4. Switch to the **Lost** tab and group by **Lost Reason**. You see why you lose.

The leads here have 0 expected revenue. That is normal, because revenue is usually added after conversion.

## Behind the scenes

- The report reads the same records as the **Leads** and **My Pipeline** menus, plus lost ones.
- A lost record is one that you marked as lost. It is archived, shown in the **Lost** tab, and has the stage label **Lost**.
- A lead keeps its history after conversion. **Conversion Date** records when it became an opportunity.
- Nothing you change on this page edits a record, except the bulk actions you start on purpose.

## See also

- [Pipeline analysis](./pipeline-analysis.md)
- [Lost reasons](../configuration/lost-reasons.md)
- [Mark won or lost](../pipeline/mark-won-lost.md)
- [Reporting overview](./index.md)
