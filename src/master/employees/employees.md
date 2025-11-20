# Employees

The **Employees** module in **AureusERP** allows businesses to create and manage employee records efficiently. Each employee profile includes personal, professional, and organizational details to support smooth HR operations.

## Employee Creation

### Use Case

This feature is used to onboard new employees into the system, manage their roles, contact details, work location, approvals, and maintain essential personal and work-related records.

### Steps to Create a New Employee

1. Navigate to **`Employees → Employees → New Employee`** as shown below.

   ![Employee create](/images1/employees/emp_create.png)

2. Fill in the following fields:

   ### Basic Details

   - **_Name:_** Full name of the employee.
   - **_Job Title:_** Role or designation (e.g., Software Engineer, HR Manager).
   - **_Work Email:_** Official email address used for internal communication.
   - **_Department:_** Select the department where the employee works.
   - **_Work Mobile:_** Mobile number used for business communication.
   - **_Job Position:_** Link to a predefined job position created in configuration.
   - **_Work Phone:_** Office phone or landline.
   - **_Manager:_** Reporting manager or supervisor.
   - **_Employee Tags:_** Add labels for easy categorization (e.g., Remote, Contract).
   - **_Coach:_** A mentor or coach assigned to the employee.

   ![Employee create](/images1/employees/emp_general.png)

   ### Work Information

   - **Location Subsection**

     - **_Work Address:_** Office address for the employee.
     - **_Work Location:_** Specific office branch, home, or other.

   - **Organization Details Subsection**

     - **_Company:_** Company name (used for multi-company setups).
     - **_Color:_** Assign a color for visual identification (optional).

   - **Approver Subsection**

     - **_Time Off:_** Person responsible for approving leave.
     - **_Attendance Manager:_** Manager who monitors attendance.

   - **Schedule Subsection**

     - **_Working Hours:_** Select from predefined working schedules.
     - **_Time Zone:_** Time zone applicable to the employee's work location.

   ![Employee create](/images1/employees/emp_work.png)

   ### Private Information

   - **Private Contact Subsection**

     - **_Street 1 / Street 2 / City / Postal Code:_** Complete home address.
     - **_Country / State:_** Residence location.
     - **_Private Phone:_** Personal phone number.
     - **_Bank Account:_** Bank account details for salary.
     - **_Private Email:_** Personal email address.
     - **_Private Car Plate:_** Vehicle registration.
     - **_Distance Home to Work:_** Commute distance.
     - **_Km Home to Work:_** Numeric value of the commute distance.
     - **_Distance Unit:_** Measurement unit (Km or m).

   ![Employee create](/images1/employees/emp_private1.png)

   - **Emergency Contact Subsection**

     - **_Contact Name:_** Name of emergency contact person.
     - **_Contact Phone:_** Emergency contact number.

   - **Family Status Subsection**

     - **_Marital Status:_** Select marital status (e.g., Single, Married).

   - **Education Subsection**

     - **_Certificate Level:_** Highest education level.
     - **_Field of Study:_** Main academic focus (e.g., Engineering, Finance).
     - **_School:_** Name of the institution.

   ![Employee create](/images1/employees/emp_edu.png)

   - **Citizenship Subsection**

     - **_Country / State:_** Place of citizenship.
     - **_Identification ID / SSN No / SIN No / Passport ID:_** Government-issued IDs.
     - **_Gender / Date of Birth / Country of Birth:_** Personal demographics.

     ![Employee create](/images1/employees/emp_citi.png)

   - **Work Permit Subsection**

     - **_Visa Number / Work Permit No:_** Relevant work authorization details.
     - **_Visa Expiration / Work Permit Expiration Date:_** Validity dates.
     - **_Work Permit (upload):_** Upload document proof.

     ![Employee create](/images1/employees/emp_workp.png)

   ### Settings

   The **Settings** section allows configuration of employment-related options, system login, and other administrative details.

   - **Employment Status Subsection**

     - **_Active Employee:_** Enable this if the employee is currently active in the organization.
     - **_Flexible Work Arrangement:_**  
       Allow flexible work timing or remote work options for this employee.
     - **_Fully Flexible Schedule:_** Enable this if the employee can manage working hours without fixed schedules.
     - **_Work Permit Scheduled Activity:_** Automatically generate scheduled activities related to the employee’s work permit expiry or renewal.
     - **_Related User:_** Assign or create a user account linked to the employee.  
       This field is used to provide login credentials to the employee by either selecting an existing user or creating a new one.
     - **_Departure Reason:_** Select the reason for departure if the employee leaves the organization.  
       Options include:
       - Fired
       - Retired
       - Resigned

   - **Attendance / Point of Sale Subsection**

     - **_Badge ID:_** Unique identification number for attendance tracking or POS access.
     - **_PIN:_** Security PIN used for login in attendance or POS systems.

   ![Employee create](/images1/employees/emp_settings1.png)

   - **Additional Information Subsection**

     - **_Primary Language:_** Default language used by the employee.
     - **_Additional Notes:_** Any additional comments or remarks.
     - **_Notes:_** Internal notes for HR reference.

   ![Employee create](/images1/employees/emp_addinfo.png)

3. Action Buttons

- **_Create:_** Save the employee profile.
- **_Create & Create Another:_** Save and open new form.
- **_Cancel:_** Exit without saving.

## Employee View (Post-Creation)

After creation, you are redirected to the **View Employee** page.

![Employee create](/images1/employees/emp_view.png)

### Edit Employee

Modify any information as needed by clicking the **Edit Employee** button.

### Manage Skills

1. Click **Manage Skills**.

2. Click **Add Skill**.
   ![Employee create](/images1/employees/emp_skill.png)

3. Fill in:
   - **_Skill Type:_** Select from configured options.
   - **_Skill:_** Specific skill (e.g., JavaScript, HR Management).
   - **_Skill Level:_** Proficiency level.
     ![Employee create](/images1/employees/emp_skill2.png)
4. Click **Create** to add the skill.

![Employee create](/images1/employees/emp_skill3.png)

### Manage Resumes

1. Click **Manage Resumes**.
2. Click **Add Resume**.
   ![Employee create](/images1/employees/emp_resu.png)

3. Fill in:
   - **_Title:_** Resume title (e.g., Resume 2025).
   - **_Type:_** Document type (Resume, Portfolio).
   - **Duration / Start Date / End Date**: Period covered.
   - **_Display Type:_** How it's shown.
   - **_Description:_** Additional notes.
     ![Employee create](/images1/employees/emp_resu1.png)
4. Click **Create** to save the resume.

![Employee create](/images1/employees/emp_resu2.png)

## Summary

The **Employees** module in **AureusERP** provides a comprehensive system for managing employee records. From creation to skill and resume management, it supports efficient HR processes and ensures that all necessary information is captured for effective workforce management.
