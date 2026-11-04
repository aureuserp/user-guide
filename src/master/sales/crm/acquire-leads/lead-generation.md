# Generate leads from visitors

Visitor rules create leads for you when people browse your website. You decide which visitors count, such as those from one country or those who open one page. Aureus then adds a lead with the tags, priority, team and salesperson you chose.

> **In simple words:** A rule watches your website and makes a lead when a visitor matches it.

This feature needs the Website app to be installed. Without it, the switch in the settings stays off.

::: info About the example
Sharma Textiles wants more enquiries from India. You create a rule named `Textile page visitors`. It makes a lead for each visitor from India who opens a page with `/textile` in its address.
:::

## Settings

Turn the feature on first.

1. Go to `CRM → Settings → Manage Lead Generation`.
2. Switch on **Visitors to Leads**.
3. Click **Save changes**.

<ImagePopup src="/images1/crm/lead-generation-settings.png" alt="Manage Lead Generation settings with Visitors to Leads switched on and the Manage Rules button" />

Once the switch is on, a line tells you how many rules are active. If there are none, it warns you that visits will not create leads until you add a rule.

- **Manage Rules** opens the list of rules.
- **Create Leads for Existing Visitors** applies the active rules to pages that visitors already opened. It shows only when at least one rule is active and some visitors have no lead. Aureus asks you to confirm, then reports how many leads it created.

## The rules list

Open `CRM → Configuration → Visitors to Leads Rules`. The page appears only when the feature is on.

<!-- TODO-SCREENSHOT: /images1/crm/visitor-rules-list.png | Visitors to Leads Rules list with columns and the Active switch -->

### Columns

The list shows **Rule Name**, **URL Expression**, **Countries**, **Type**, **Sales Team**, **Salesperson**, **Leads**, **Opportunities** and **Active**.

- **URL Expression** shows **Whole website** when the rule has no expression.
- **Countries** shows **All countries** when the rule has none.
- **Leads** and **Opportunities** count what the rule created.
- Click the **Active** switch to turn a rule on or off.

### Search, filter and order

- Type in the search box to find a rule by name.
- Use the **Active** filter to show active or inactive rules.
- Drag a row to change the order. The first matching rule wins when a visitor fits more than one.
- Row actions are **View**, **Edit** and **Delete**. Bulk actions let you export or delete ticked rules.

## Create a rule

1. Go to `CRM → Configuration → Visitors to Leads Rules`.
2. Click **New Visitors to Leads Rule**.
3. Fill in the form.
4. Click **Create**. Use **Create & create another** to save and open an empty form.

<ImagePopup src="/images1/crm/visitor-rule-form.png" alt="Create Visitors to Leads Rule form filled in for textile page visitors from India" />

### Rule

- **_Rule Name:_** A clear name for the rule. Required, up to 255 characters. The hint reads **e.g. US Visitors**.

**Example:** `Textile page visitors`.

### Website Traffic Conditions

- **_Countries:_** Only visitors from these countries match. Aureus finds the country from the visitor's IP address. Leave it empty for all countries.
- **_States:_** Only visitors from these states match. It shows after you pick a country. Aureus knows the state only for logged-in customers, from their address. Leave it empty for all states.
- **_URL Expression:_** The pages that count. Enter a regular expression on the page path. Leave it empty for the whole website. Enter `/` for the home page only. Enter `/pricing|/shop` for pages that contain `/pricing` or `/shop`. An invalid expression is rejected with the message **Enter a valid expression.**

**Example:** Pick **India** as **Countries**. Enter `/textile` as **URL Expression**.

### Contact Filter

This section shows only when **Data Tracking** is **Companies and their contacts**. A note reminds you to check whether you must follow data protection law (GDPR) when you store personal data.

- **_Number of Contacts:_** **1 contact** to **5 contacts**. It starts at **1 contact**. Required.
- **_Filter Contacts On:_** Choose **Role** or **Seniority**. It starts as **Role**. Required.
- **_Preferred Role:_** The main role you look for. It shows for **Role**. Pick one, or type a new name to add it.
- **_Other Roles:_** More roles you accept. It shows after you pick a **Preferred Role**.
- **_Seniority:_** The level you look for. It shows for **Seniority**. Pick one, or type a new name to add it.

### Lead Data

The title of this section is **Opportunity Data** when the **Type** is **Opportunity**.

- **_Tags:_** Tags added to each lead the rule creates. You can pick many. See [Tags](../configuration/tags.md).
- **_Suffix:_** Text added to the end of the lead name. For example, `Website visitor #12 (India) - Pricing`.
- **_Priority:_** The priority of the new lead. It starts as **Low**.
- **_Sales Team:_** The team that receives the lead.
- **_Company:_** The company the lead belongs to. Leave it empty to use the customer's company, or the first active company.
- **_Salesperson:_** The owner of the lead. The list depends on the **Company** you chose.

**Example:** Add the tag **Software**. Set **Suffix** to `Textile page`, **Priority** to **High**, and **Sales Team** to **Sales**.

### Settings

- **_Active:_** Turns the rule on. It starts on.
- **_Data Tracking:_** Choose **Companies** or **Companies and their contacts**. It starts as **Companies**. Required.
- **_Type:_** Choose **Lead** or **Opportunity**. It shows only when **Lead Qualification** is on. Then it starts as **Lead**. Required.

### Lead Generation Conditions

The title is **Opportunity Generation Conditions** when the **Type** is **Opportunity**.

- **_Industries:_** The industries you target. Pick many, or type a name to add a new industry.
- **_Filter on Size:_** Switch on to limit by company size. It starts on.
- **_Company Size From:_** The smallest number of employees. It starts at 0. Required when the size filter is on.
- **_Company Size To:_** The largest number of employees, shown with the unit **employees**. It starts at 1000 and cannot be lower than **Company Size From**. Required when the size filter is on.

## The rule page

A saved rule opens with three tabs: **View**, **Edit** and **Generated Leads**. A number on **Generated Leads** shows how many records the rule created. The tab lists their **Name**, **Country**, **Stage** and **Created** date.

## Behind the scenes

- Aureus watches each visitor page view. If an active rule matches the page and the place, it queues the visit and creates the lead.
- A visitor gets one lead only. If more than one rule matches, the first rule in the list order is used.
- The lead name is `Website visitor #<number>`, with the country in brackets when known. For a logged-in customer it is `Website visitor: <customer name>`. Your **Suffix** follows after a hyphen.
- The lead copies the customer's name, email, phone and address when the visitor is a known customer. **Referred By** shows **Website Visitor**.
- The **Notes** field lists the rule, IP address, country, time zone, language, landing page and first visit date. The lead page also shows the **IP Address**.
- The lead is created as a **Lead** only when the rule **Type** is **Lead** and **Lead Qualification** is on. Otherwise it is an opportunity.
- Leads from a rule appear in `CRM → Leads → Leads` like any other lead.

::: tip
Test a rule with a narrow **URL Expression** first. A broad rule can create many leads in a day.
:::

## See also

- [Create a lead](./create-lead.md)
- [Convert a lead](./convert-lead.md)
- [Tags](../configuration/tags.md)
- [CRM settings](../configuration/settings.md)
