# Configuration

This guide explains the configuration options available in the **Time Off Plugin**. These configurations help manage leave types, accruals, holidays, and activities efficiently.

## Leave Types

Leave Types define different categories of employee leave such as sick leave, vacation, or paid time off. These help structure the time-off process for approvals, allocations, and tracking.

### Steps to Create a New Leave Type

1. Navigate to **Time Off >> Configuration >> Leave Types >> New Leave Type** as shown below.

   ![Config. New Leave](../../../images1/time-off/config_leave.png)

2. Fill out the form:

   ### General Information

   - **Title:** Name of the leave type (e.g., Paid Leave).

   - **Approval:** Choose who approves the leave:

     - No Validation
     - By Time Off Officer
     - By Employee's Approver
     - By Both Approver and Officer

   - **Requires Allocation:** Should employees request an allocation for this leave?

     - Yes: Additional fields will appear.
     - No Limit: Unlimited leave days.

   - **Employee Requests (only if 'Yes' above):**

     - Extra Days Request Allowed
     - Not Allowed

   - **Approval (if 'Yes' above):**

     - Same options as the first Approval section.

   ### Display Option

   - **Color:** Choose a color to represent the leave type.

   ### Configuration

   - **Notified Time Off Officers:** Select users who will be notified.
   - **Take Time Off In:** Choose unit of leave:

     - Day, Halfday, Hour

   - **Public Holiday Included:** Toggle to include/exclude public holidays.
   - **Allow to Attach Supporting Document:** Toggle to allow document upload.
   - **Show on Dashboard:** Toggle to show on employee dashboard.
   - **Kind of Time Off:** Select type:

     - Absence or Worked Time

   - **Allow Negative Cap:** Toggle to allow taking more leave than balance.

3. Actions

- **Create**
- **Create & create another**
- **Cancel**

## Accrual Plan

Automatically manage the accumulation of leave over time.

### Steps to Create a New Accrual Plan

1. Navigate to **Time Off >> Configuration >> Accrual Plan >> New Accrual Plan** as shown below.

2. Fill in:

   - **Title:** Name of the plan (e.g., Monthly Paid Leave).
   - **Is Based on Worked Time:** Toggle if leave accrues based on work.
   - **Accrued Gain Time:** Select when time is accrued:

     - Start or End of accrual period.

   - **Carry Over Time:** Toggle and choose when unused leave is carried:

     - Start of year, Allocation date, or Custom date.

   - **Carry Over Date:** Set day and month if "Other" selected.
   - **Status:** Enable or disable plan.

3. Actions

- **Create**, **Create & create another**, **Cancel**

### After Creation: Manage Milestones

- Click **Manage Milestone**
- Click **New Leave Accrual Plan** and fill:

  - **Accrual Amount & Type:** Days or Hours.
  - **Accrual Frequency:** Hourly to Yearly options.
  - **Accrual Day:** Select specific days.
  - **Cap accrued time:** Toggle and set max days.
  - **Start Count:** When to begin accrual (Years/Days/Months).
  - **Advanced Accrual Settings:**

    - Reset to zero, carry over, or max carry over.
    - Set Milestone Cap and Accrual Validity.

### Actions

- **Create**, **Create & create another**, **Cancel**

## Public Holidays

Mark public holidays so leave calculations can consider them.

### Steps to Create Public Holidays

1. Navigate to **Time Off >> Configuration >> Public Holidays >> New Public Holiday**
2. Fill in:

   - **Name:** Holiday name (e.g., Independence Day)
   - **Start Date / End Date:** Date range
   - **Calendar:** Assign calendar

3. Actions

- **Create**, **Create & create another**, **Cancel**

## Mandatory Days

Mark days where taking leave is mandatory (e.g., shutdowns).

### Steps to Create Mandatory Days

1. Navigate to **Time Off >> Configuration >> Mandatory Days >> New Mandatory Day**
2. Fill in:

   - **Color:** Choose a color for display
   - **Name:** Name of the day/event
   - **Start Date / End Date:** Date range

3. Actions

- **Create**, **Create & create another**, **Cancel**

## Activity Types

Set activity types for follow-ups, file uploads, meetings, etc.

### Steps to Create Activity Types

1. Go to **Time Off >> Configuration >> Activity Types >> New Activity Type** as shown below.
2. Fill in:

   ### General Information

   - **Activity Type:** Select from predefined options.
   - **Action:** Define action type.
   - **Default User:** Assign default person.
   - **Summary:** Short description.
   - **Note:** Additional information.

   ### Advanced Information

   - **Icon:** Visual icon for activity.
   - **Decoration Type:** Alert or Error styling.
   - **Chaining Type:** Link activities.

     - Suggest or Trigger next.

   - **Suggest/Trigger:** Define follow-up action.

   ### Status & Configuration

   - **Status:** Toggle active/inactive.
   - **Keep Done Activities:** Archive or remove after done.

   ### Delay Information

   - **Delay Count:** Time delay.
   - **Delay Unit:** Time unit.
   - **Delay Form:** When delay applies.

3. Actions

- **Create**, **Create & create another**, **Cancel**

---

This completes the **Time Off Plugin Configuration** guide. Each setting ensures that leave management, public holidays, and related activities are tailored to your organization’s needs.
