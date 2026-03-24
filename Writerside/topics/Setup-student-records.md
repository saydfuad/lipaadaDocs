# Setup

To begin setting up the **Student Records** module, navigate to the **SETUP** section and follow these steps:

## Classroom Registration
To start using **LIPA ADA** you must have list of **Classroom** as per your school.

1. Click on **Classes** and then select **Add Classroom** as shown in Figure 1 below. Fill in the required details: **Classroom Name**, **Level**, **Number of Terms**, **Report Card Design**, and set the **Status** to *ACTIVE*.
2. If your **Classroom** has only one **Stream**, click **Add** to create the classroom. If it has multiple streams, proceed to **Streams** and add each stream (e.g., *A*, *B*, etc.).
3. We will return later to assign a **Class Teacher** and verify subjects, but this is not necessary for the initial setup.

![](Add class.PNG)

## Student Import

We provide an easy way to import your students from an Excel file. Follow the steps below to complete the process:

1. Navigate to **Student Import** and download the provided **Template**.
2. Use the template to fill in the student records according to the specified columns in the Excel file.
3. Return to **LIPA ADA** and upload the updated file. Select the appropriate **Classroom**, **Stream**, and **Academic Year**.
4. Click **Import** to validate and import the data. If there are any errors, the system will display helpful information to guide you through the next steps.

![](import1.PNG)  Figure 1
**Note:** *You must fill a separate file for each **Stream** within the same **Classroom***

## Subjects Registration

Adding **Subjects** to a **Classroom** is not mandatory to start using **LIPA ADA** Finance and **Admission** modules, but it is necessary if you need to track student results.

To start adding **Subjects**, follow these steps:

1. Navigate to **Subjects** and click **Add Subject**.
2. Fill in the form as shown in Figure 2 below. Important fields to consider:
    - **Subject Name**: This should match the name of the same subject across all **Classrooms**.
    - **Classroom**: Select the **Classroom** where you want to add this **Subject**.
    - **Subject Code**: For example, for English taught in Grade 6, you could use **ENG6**.
3. We have grouped subject marking into **TEST 1**, **TEST 2**, and **EXAM**. Define the percentage weight for each as needed.
4. Under **Classification**, choose **Mandatory** if the **Subject** is required and will be considered when evaluating student performance.
5. If you have already registered users as **Teachers**, you can assign a teacher to this subject for the selected class, but this is not mandatory at this stage.**Note:** *Only teacher assigned to subject can post results using **Direct Post***
6. Click **Add** to finish adding the **Subject**. Repeat the process for all other **Subjects** in the same class.
![](Subject update.PNG) Figure 2

## Grade Setup

**LIPA ADA** uses your grading system to analyze results and provide valuable insights into student performance. Since this is a one-time setup, take extra time to ensure accuracy.

Setting up the grading system is straightforward; just follow these steps:

1. Navigate to **Grade** and click **Add Grade**.
2. A box will open, allowing you to choose a **Grading System Structure**. Select **Level Based Grading**, which is common for most situations.
3. Choose the relevant **Level** (e.g., Secondary).
4. Enter the **Minimum** and **Maximum** values for the range, and under **Symbol**, enter the grade (e.g., A, B, C).
5. Use the **Definition** field to add a remark for the grade (e.g., **EXCELLENT** for grade **A**).

**Note:** When adding grades for a particular **Level**, ensure that the minimum and maximum values cover all possible marks that a student might achieve. For example, if you set the minimum as 0 and the maximum as 34 for **F**, and then set the minimum as 36 and the maximum as 54 for **D**, you will miss the grade for a student who scores 35, as it wouldn't fall within any of the defined ranges.
![](grade update.PNG) Figure 3

## Report Card Comments

Instead of manually writing comments on each student's report card, **LIPA ADA** allows you to predefine comments based on a range of student scores. These comments can be set separately for the **Head Teacher (Principal)** and the **Class Teacher**.

To set up predefined report card comments, follow these steps:

1. Navigate to **Report Comments** and click **Add Comment**.
2. Select the **Level** (e.g., **Secondary**) and choose whether the comment is for the **Principal** or the **Class Teacher**.
3. Write the actual comment you want to appear on the report card.
4. Enter the **Minimum** and **Maximum** average score range that will trigger this comment to appear on a student's report card.
5. Repeat this process for each possible score range, as shown in Figure 4 below.

![](result comment 2.PNG) Figure 4

## Timetable
### Managed Timetable
## Manage Timetable

We provide an easy way to view and manage class timetables within the system. Follow the steps below to explore and monitor the timetable:

Navigate to **Timetable → Manage Timetable** from the sidebar.

Use the filters at the top to select the appropriate **Class**, **Stream**, **Teacher**, and **Week** (e.g., Current Week).

Choose your preferred view:
- **Class View** to see the timetable by class
  ![](manage timetabls update.PNG)
- **Teacher View** to see the timetable by teacher
![](teacher2.PNG)

The system will display a timetable grid showing days (Monday to Friday) and periods. Each cell represents a scheduled subject or activity.

Review the **Quick Stats** section to see:
- Number of filled slots
- Number of free slots
- Overall timetable coverage (%)

Use the **Legend** to understand the meaning of colors:
- Blue for regular subjects
- Yellow for breaks or non-academic activities
- Green for free periods
- Red for conflicts (hover to see more details






### Auto Generator
Automatically creates timetables for selected classes using a **smart scheduling algorithm**.
To starting set auto generator timetable, follow this steps:
1. Navigate | Go to **Setup → Timetable → Manage Timetable** 
2. Review | Check or edit existing timetables 
3.  Auto Generate | Click **Auto Generate** for automated scheduling 
4.  Configure | Set class, periods/day, teacher limits, and mode 
5.  Generate | Click **Generate Timetable** 
6. Review | View generated timetable and adjust manually if needed 
Fill in the form as shown in Figure  below. Important fields to consider:
![](auto generate.PNG)
-  **Generation Settings**
This area lets you define how the automatic timetable will be generated.
 **Select Class**  Choose the class whose timetable you want to generate. 
 **Max Periods/Day**  Maximum number of lessons per day (e.g., 8). 
 **Teacher Max/Day**  Maximum number of lessons per teacher per day. 
 **Lunch Period**  Time slot reserved for lunch breaks. 
 **Performance Mode**  Controls how fast and detailed the generation will be. Options: Fast, Balanced, Thorough.
---
- **Options**
These checkboxes help refine generation behavior:
**Clear existing timetable** Deletes any previous timetable for the selected class before generating a new one. |
**Include lunch breaks** Ensures lunch periods are added automatically. |
**Balance teacher workload** Distributes classes evenly across teachers to prevent overloading. |

- **Performance Modes**
Choose how the system generates schedules depending on speed and quality.
 **Fast**  50 attempts, 10s Quick generation with basic balancing. 
 **Balanced** 500 attempts, 25s  Default mode – good balance of speed and accuracy. 
 **Thorough** 2000 attempts, 45s Best quality with full workload optimization.

- **Generation Log**
  Displays progress or errors during the timetable generation process.
 **Log Output**  Shows live updates during generation. 
 **Clear Button** | Resets the log area for new generation runs. 

### **How It Works**
  The **Smart Algorithm** automatically:
- Analyzes subject requirements.
- Balances teacher workloads.
- Optimizes classroom and room usage.
- Avoids teacher double-booking and scheduling conflicts.

**Constraints applied:**
- Core subjects are placed in the morning.
- Physical activities scheduled in the afternoon.
- Daily workload is balanced for each teacher and class.


####  **Quality Scoring**
After generation, the timetable receives a **quality score** based on efficiency and fairness:
90–100%  **Excellent** 
70–89%  **Good** 
50–69%  **Acceptable**
Below 50%  Needs improvement


####  **Generation Log**
Displays progress or errors during the timetable generation process.
**Log Output**  Shows live updates during generation. 
**Clear Button**  Resets the log area for new generation runs.


#### **Generate Timetable Button**
Once all settings are configured:
1. Select the desired class.
2. Adjust the performance mode.
3. Click **Generate Timetable**.
4. Wait for the algorithm to complete (usually 20–30 seconds).
5. Review results in **Manage Timetable** or **Grid View**.


### **Navigation Buttons**
 **Back to List**  Returns to Manage Timetable page. 
 **Grid View**  Switches to the timetable visualization interface.


### Timetable Grid
Displays the weekly timetable visually by **day and time period**.  

##Steps:
1. Navigate to **Timetable** click **Timetable Grid**
2. **Select class dropdown** Choose which class timetable to view. 
3. **Week Filter:** Switch between current or past/future weeks. 
4. **List View / Print Buttons:** Switch display format or print the grid. 

![](timetable grid.PNG)

### Summary 
**Timetable Table:** Shows each day’s schedule with time slots.
- *Free Period* – no subject assigned
- *Regular Period* – subject assigned
- **Quick Stats:**
    - Filled Slots
    - Free Slots
    - Coverage percentage
- **Legend:** Explains color codes
    - 🟦 Regular Subject
    - 🟧 Break / Non-Academic
    - ⬜ Free Period

**Usage Tip:**  
Use **Timetable Grid** after generation or manual edits to verify that all periods are correctly allocated.

### Manage Room
Define and manage available rooms and learning spaces used in scheduling.
### To access the **Manage Rooms** section:
1. Go to **Timetable** click **Manage Rooms** 

 ![](manage room.PNG)

### Steps to **Add Room**
### Step 1: Open Manage Rooms
- Go to the **Setup** menu on the sidebar.
- Click **Timetable**.
- Select **Manage Rooms** from the dropdown.
- The system will display the list of existing rooms (if any).



### Step 2: Click on "Add Room"
- Click the **Add Room** button (usually at the top-right or above the list).
- A form will appear for entering room details.


### Step 3: Fill in Room Details
Enter the following fields:
- **Room Name** → Example: *Science Lab*, *Classroom 1A*
- **Room Type** → Choose *Classroom*, *Lab*, *Computer Room*,Library,Hall etc.
- **Capacity** → Number of seats that can fit in the room
- **Room Code** → example: **SL1, ** CLA**
- **Status** → Set as *Active* or *Inactive*
- **Description** → additional details about the room.


### Step 4: Save the Room
- After filling in details, click the **Add** button.
- The new room will now appear in the room list and become available for timetable allocation.

![](add room.PNG)

## Additional Options
- **Edit Room:** Modify an existing room’s details.
- **Delete Room:** Remove a room from the system (only if not in use).
- **Search/Filter:** Quickly locate rooms by name or type.

##Notes
- Rooms must be created **before** generating or assigning timetables.
- Ensure each room has a **unique name** to prevent confusion in scheduling.
- Room assignments are automatically optimized by the **Auto Generator**.

### Set Period
The **Set Period** feature in **Lipa Ada** defines the daily structure of class sessions.  
Each period represents a specific block of time during which a subject or activity takes place.  
Setting periods ensures proper timetable generation and scheduling.

### To access the **Set Period** section:
1. Navigate to **Timetable** click **Set Period**

![](set period.PNG)

## Steps to **Add Period**
### Step 1: Open Set Period Page
- From the **Setup** menu on the left sidebar, click **Timetable**.
- Choose **Set Period** from the dropdown list.
- The system will display all existing periods in a tabular list (if any are already configured).


### Step 2: Click **Add  Period**
- Press the **Add Period** button (usually on the top-right of the page).
- A form will appear to enter new period details.

### Step 3: Fill in Period Details
Provide the following details in the form:
**Start Time**  The time the period begins  e.g *08:00 AM* 
**End Time**  The time the period ends  *09:00 AM* 
**Title** e.g **regular Period**, **Break**
**Level** choose level e.g **Nur**, **prim** , **Sec** and **Advance**.


### Step 4: Save the Period
- Click **Add**  to confirm your entry.
- The new period will now be listed in the table and available for use in timetable generation.


###  Additional Actions
- **Edit:** Modify timing or name of an existing period.
- **Delete:** Remove a period (only if not yet used in any timetable).

![](add period.PNG)
## 💡 Notes
- Periods must be set before using **Auto Generator** or **Manage Timetable**.
- Avoid overlapping time ranges to prevent scheduling conflicts.
- Ensure lunch or break periods are clearly marked for accurate timetable creation.




 



 