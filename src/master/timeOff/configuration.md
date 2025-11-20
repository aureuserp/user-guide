# Configuration

This guide explains the configuration options available in the **Time Off Plugin**. These configurations help manage leave types, accruals, holidays, and activities efficiently.

## Leave Types

Leave Types define different categories of employee leave such as sick leave, vacation, or paid time off. These help structure the time-off process for approvals, allocations, and tracking.

### Steps to Create a New Leave Type

1. Navigate to **`Time Off → Configuration → Leave Types → New Leave Type`** as shown below.

   ![Config. New Leave](/images1/time-off/config_leave.png)

2. Fill out the form:

   ### General Information

   - **_Title:_** Name of the leave type (e.g., Paid Leave).
   - **_Approval:_** Choose who approves the leave:
     - No Validation
     - By Time Off Officer
     - By Employee's Approver
     - By Both Approver and Officer
   - **_Requires Allocation:_** Should employees request an allocation for this leave?
     - Yes: Additional fields will appear.
     - No Limit: Unlimited leave days.
   - **_Employee Requests (only if 'Yes' above):_**
     - Extra Days Request Allowed
     - Not Allowed
   - **_Approval (if 'Yes' above):_**

     - Same options as the first Approval section.

     ![General Leave](/images1/time-off/leave_general.png)

   ### Display Option

   - **_Color:_** Choose a color to represent the leave type.

   ### Configuration

   - **_Notified Time Off Officers:_** Select users who will be notified.
   - **_Take Time Off In:_** Choose unit of leave:
     - Day, Halfday, Hour
   - **_Public Holiday Included:_** Toggle to include/exclude public holidays.
   - **_Allow to Attach Supporting Document:_** Toggle to allow document upload.
   - **_Show on Dashboard:_** Toggle to show on employee dashboard.
   - **_Kind of Time Off:_** Select type:

     - Absence or Worked Time

   - **_Allow Negative Cap:_** Toggle to allow taking more leave than balance.

   ![General Leave](/images1/time-off/leave_config.png)

3. Actions

   - **_Create_**
   - **_Create & create another_**
   - **_Cancel_**

## Accrual Plan

Automatically manage the accumulation of leave over time.

### Steps to Create a New Accrual Plan

1. Navigate to **`Time Off → Configuration → Accrual Plan → New Accrual Plan`** as shown below.

   ![Config. New Leave](/images1/time-off/config_accrual.png)

2. Fill in:

   - **_Title:_** Name of the plan (e.g., Monthly Paid Leave).
   - **_Is Based on Worked Time:_** Toggle if leave accrues based on work.
   - **_Accrued Gain Time:_** Select when time is accrued:

     - Start or End of accrual period.

   - **_Carry Over Time:_** Toggle and choose when unused leave is carried:

     - Start of year, Allocation date, or Custom date.

   - **_Carry Over Date:_** Set day and month if "Other" selected.
   - **_Status:_** Enable or disable plan.

   ![Config. New Leave](/images1/time-off/general_accrual.png)

3. Actions

   - **_Create_**
   - **_Create & create another_**
   - **_Cancel_**

### After Creation: Manage Milestones

![Config. New Leave](/images1/time-off/milestone_accrual.png)

- Click **Manage Milestone**
- Click **New Leave Accrual Plan** and fill:
  ![Config. New Leave](/images1/time-off/new_milestone_accrual.png)

  - **_Accrual Amount & Type:_** Days or Hours.
  - **_Accrual Frequency:_** Hourly to Yearly options.
  - **_Accrual Day:_** Select specific days.
  - **_Cap accrued time:_** Toggle and set max days.
  - **_Start Count:_** When to begin accrual (Years/Days/Months).
  - **_Advanced Accrual Settings:_**

    - Reset to zero, carry over, or max carry over.
    - Set Milestone Cap and Accrual Validity.

  ![Config. New Leave](/images1/time-off/general_milestone_accrual.png)

### Actions

- **_Create_**
- **_Create & create another_**
- **_Cancel_**

## Public Holidays

Mark public holidays so leave calculations can consider them.

### Steps to Create Public Holidays

1. Navigate to **`Time Off → Configuration → Public Holidays → New Public Holiday`** as shown below.

   ![Config. New Leave](/images1/time-off/new_public.png)

2. Fill in:

   - **_Name:_** Holiday name (e.g., Independence Day)
   - **_Start Date / End Date:_** Date range
   - **_Calendar:_** Assign calendar

   ![Config. New Leave](/images1/time-off/general_public.png)

3. Actions

   - **_Create_**
   - **_Create & create another_**
   - **_Cancel_**

## Mandatory Days

Mark days where taking leave is mandatory (e.g., shutdowns).

### Steps to Create Mandatory Days

1. Navigate to **`Time Off → Configuration → Mandatory Days → New Mandatory Day`** as shown below.

   ![Config. New Leave](/images1/time-off/new_mandatory.png)

2. Fill in:

   - **_Color:_** Choose a color for display
   - **_Name:_** Name of the day/event
   - **_Start Date / End Date:_** Date range

   ![Config. New Leave](/images1/time-off/general_mandatory.png)

3. Actions

   - **_Create_**
   - **_Create & create another_**
   - **_Cancel_**

## Activity Types

Set activity types for follow-ups, file uploads, meetings, etc.

### Steps to Create Activity Types

1. Go to **`Time Off >> Configuration >> Activity Types >> New Activity Type`** as shown below.

![Config. New Leave](/images1/time-off/new_activity.png)

2. Fill in:

   ### General Information

   - **_Activity Type:_** Select from predefined options.
   - **_Action:_** Define action type.
   - **_Default User:_** Assign default person.
   - **_Summary:_** Short description.
   - **_Note:_** Additional information.

   ### Advanced Information

   - **_Icon:_** Visual icon for activity.
   - **_Decoration Type:_** Alert or Error styling.
   - **_Chaining Type:_** Link activities.

     - Suggest or Trigger next.

   - **_Suggest/Trigger:_** Define follow-up action.

   ### Status & Configuration

   - **_Status:_** Toggle active/inactive.
   - **_Keep Done Activities:_** Archive or remove after done.

   ### Delay Information

   - **_Delay Count:_** Time delay.
   - **_Delay Unit:_** Time unit.
   - **_Delay Form:_** When delay applies.

   ![Config. New Leave](/images1/time-off/general_activity.png)

3. Actions

   - **_Create_**
   - **_Create & create another_**
   - **_Cancel_**

---

This completes the **Time Off Plugin Configuration** guide. Each setting ensures that leave management, public holidays, and related activities are tailored to your organization’s needs.
