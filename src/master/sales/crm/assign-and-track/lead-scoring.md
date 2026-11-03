# Lead scoring

Lead scoring gives each open lead and opportunity a probability of winning. Aureus works it out from your own history of won and lost deals. You can then focus on the records with the best chance first.

> **In simple words:** Aureus learns from your past wins and losses to guess which new records will win.

The score is a percentage. It updates when a record changes and when you rebuild the scoring from the settings page.

::: info About the example
The Sharma Textiles lead is in the first stage, has a valid email and phone, comes from the **Newsletter** source and carries the tag **Software**. You check what Aureus considers for it.
:::

## Settings

1. Go to `CRM → Settings → Manage Lead Scoring`.
2. Choose the details Aureus should consider.
3. Set a start date if you want to ignore old records.
4. Click **Save changes**, or click **Update Scoring Probabilities**.

<!-- TODO-SCREENSHOT: /images1/crm/lead-scoring-settings.png | Manage Lead Scoring settings with criteria ticked and a start date -->

The page text reads: the probability of winning each open lead and opportunity is computed from your won and lost history. Stage and sales team are always used.

- **_Also consider:_** Tick the details to add. The helper text reads **Which details of a record the probability takes into account.**
  - **Country:** Where the record is located.
  - **State:** The state of the record.
  - **Phone quality:** Whether the phone number looks valid (at least 7 digits).
  - **Email quality:** Whether the email address looks valid.
  - **Source:** Where the record came from.
  - **Tags:** The tags on the record.
- **_Consider leads created as of the:_** A date, not later than today. Aureus learns only from records created on or after it. Leave it empty to use the whole history.

**Example:** Tick **Country**, **Email quality** and **Source**. Leave the date empty.

The stage and the sales team are always used. They have no tick box.

## Update the scores

**Update Scoring Probabilities** saves your choices, learns again from the won and lost history, and recomputes every open record.

1. Click **Update Scoring Probabilities**.
2. Read the message and confirm.

Aureus then shows **Probabilities updated for N open record(s).** Clicking **Save changes** does the same when you changed the details or the date.

## How it works

Aureus counts, for each sales team, how often each detail appeared on won records and on lost records.

- A **won** record is one in a stage marked as won.
- A **lost** record is one you marked as lost or deleted.
- For each detail on an open record, such as its stage or its country, Aureus checks if that detail is more common on won or on lost records. It combines all the details into one percentage.
- If the team has no history, Aureus uses the history of all teams together.
- The result never goes above 99.99 %. Only a won stage gives 100 %.

**Example:** In the Qualified stage with your Sales team, past records were often won. A valid email also helps. The probability goes up. If similar records were mostly lost, it goes down.

## See the reasons

Open the lead or opportunity and click the information icon next to **Probability**. The window **Probability details** shows:

- **Computed probability:** The value Aureus calculated. If there is not enough history, you see **Not enough won and lost history yet to compute a probability.**
- **Sales team:** The team whose history was used.
- **Top Positives:** Up to three details that raise the chance, such as **Has a valid email address**.
- **Top Negatives:** Up to three details that lower the chance, such as **Has no valid phone number**.

<!-- TODO-SCREENSHOT: /images1/crm/lead-probability-details.png | Probability details window with computed probability, top positives and top negatives -->

## Automatic and manual probability

- With the field empty, the probability is **Automatic**. Aureus updates it when the record changes.
- If you type your own number, it stays. The details window then adds the note that you set it by hand.
- Click **Use computed probability** to go back to the automatic value.
- Typing the same number as the computed one counts as automatic.

## Behind the scenes

- The stage, sales team, country, state, source, email, phone and probability are watched. Changing one rescores the record.
- Marking a record as lost, deleting it or restoring it triggers a new learning pass.
- Moving an opportunity to a won stage sets its probability to 100 %. Moving it out of that stage makes it automatic again.
- Reports show the probability next to the expected revenue. See [Forecast](../reporting/forecast.md) and [Pipeline analysis](../reporting/pipeline-analysis.md).

::: tip
Run **Update Scoring Probabilities** after you close many deals. More history gives better scores.
:::

::: warning
Scoring needs history. With few won and lost records, the numbers are not reliable.
:::

## See also

- [Create a lead](../acquire-leads/create-lead.md)
- [Manage opportunities](../pipeline/manage-opportunities.md)
- [Pipeline analysis](../reporting/pipeline-analysis.md)
- [Assign and track](./index.md)
