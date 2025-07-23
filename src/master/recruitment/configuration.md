# Configuration

This document explains the **Configuration** section of the Recruitment Plugin in **AureusERP**. Configuration is crucial for setting up the hiring process, including job positions, applicants, and candidate evaluation. Below is a detailed explanation of each configurable item in simple and clear language.

## Activity Plans

**Purpose**: Activity Plans help in planning and organizing steps in the recruitment process, such as initial screening, interviews, etc.

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Activities >> Activity Plans`

- Click **New Activity Plan**
- Fill in:

  - **Name**: Title of the activity plan (e.g., Initial Interview Plan)
  - **Department**: The department for which this plan is applicable
  - **Company**: The company where the recruitment is taking place
  - **Status**: Set whether the activity plan is active

- Click **Create** or **Create & Create Another**

## Activity Types

**Purpose**: Define specific types of recruitment actions (e.g., phone call, meeting, upload documents).

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Activities >> Activity Types`
- Click **New Activity Type**
- Fill in:

### General Information:

- **Activity Type**: Select from existing types or define new
- **Action**: Specify what action will be triggered (e.g., Open Form, Upload File)
- **Default User**: Person assigned to handle this activity by default
- **Summary**: Short description
- **Note**: Additional details

### Advanced Information:

- **Icon**: Visual icon to represent this activity
- **Decoration Type**: Alert type (Alert/Error)
- **Chaining Type**: Whether to suggest or trigger next activity automatically
- **Suggest/Trigger**: Choose the next activity based on chaining type

### Status & Configuration:

- **Status**: Whether this activity type is active
- **Keep Done Activities**: Whether to keep record of completed ones

### Delay Information:

- **Delay Count** and **Unit**: Set delays (e.g., 2 Days)
- **Delay From**: Choose between previous deadline or completion date

## Tags

**Purpose**: Tags help categorize applications (e.g., Urgent, Skilled, Fresher)

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Applications >> Tags`
- Click **New Tag**
- Fill in:

  - **Name**
  - **Color** (for easy identification)

## Degrees

**Purpose**: Define the academic qualifications applicable for a position.

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Applications >> Degrees`
- Click **New Degree**
- Enter the **Name** (e.g., MBA, B.Tech)

## Refuse Reasons

**Purpose**: Set predefined reasons for rejecting applicants.

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Applications >> Refuse Reasons`
- Click **New Refuse Reason**
- Fill in:

  - **Name**: Reason (e.g., Lack of Experience)
  - **Template**: Select appropriate template (e.g., Applicant Refused, Not Interested)

## Mediums

**Purpose**: Define marketing or application mediums (e.g., Social Media, Job Portal).

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> UTMs >> Mediums`
- Click **New Medium**
- Enter **Name** (e.g., LinkedIn, Indeed)

## Sources

**Purpose**: Identify sources from where applicants are coming.

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> UTMs >> Sources`
- Click **New Source**
- Enter **Name** (e.g., Referral, College Drive)

## Skill Types

**Purpose**: Define skills required in employees (e.g., Programming, Communication).

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Employees >> Skill Types`
- Click **New Skill Type**
- Fill in:

  - **Name**
  - **Color**
  - **Status**: Enable/Disable toggle

## Departments

**Purpose**: Organize your company structure by departments (e.g., HR, Development).

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Employees >> Departments`
- Click **New Department**
- Fill in:

  - **Name**
  - **Parent Department**: (Optional)
  - **Manager**
  - **Company**
  - **Color**: Tag color

## Stages

**Purpose**: Define steps in the recruitment pipeline (e.g., Applied, Interview, Hired).

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Job Positions >> Stages`
- Click **New Stage**

### General Information:

- **Stage Name**: Name of the stage
- **Requirements Department**: Related department

### Tooltips:

- **Gray/Red/Green Label**: Custom tooltips for visual cues

### Additional Info:

- **Folded**: Collapse this stage on Kanban
- **Hired Stage**: Marks the stage as final
- **Default Stage**: Set as initial stage

## Employment Types

**Purpose**: Define job types like Full-Time, Part-Time, Internship.

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Job Positions >> Employment Types`
- Click **New Employment Type**
- Fill in:

  - **Employment Type** (e.g., Internship)
  - **Country**

## Job Positions

**Purpose**: Add and manage open positions in your organization.

**Steps to Create**:

- Navigate to: `Recruitments >> Configuration >> Job Positions >> Job Positions`
- Click **New Job Position**

### Employment Information:

- **Job Position Title**: Name of the job (e.g., Software Engineer)
- **Department**: Choose from the list or create
- **Country**: Job location country
- **Manager**: Person responsible for this position
- **Company**: Select the company
- **Recruiter**: Recruiter responsible
- **Interviewers**: Add interviewers
- **Job Location**: Office location
- **Industry**: Related industry
- **Job Description**: Detailed job overview
- **Job Requirements**: Required qualifications/skills
- **Date From / To**: Recruitment duration
- **Recruitment Target**: Number of people to recruit
- **No. of Employees**: Existing count
- **Expected Employees**: Planned employee count
- **No. of Hired Employees**: Final count hired
- **Expected Skills**: Skills needed (select from list)
- **Employment Type**: Select from previously created types
- **Status**: Toggle to enable/disable the position

---

This configuration ensures the recruitment process is smooth, structured, and aligned with organizational needs. Once set up, it empowers HR teams to streamline hiring workflows.
