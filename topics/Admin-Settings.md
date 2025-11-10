# Admin_Settings

---
## Manager users
This section allows administrators to view, add, and manage user accounts and includes features for
searching users by name or email, adding new users, managing user roles and permissions and viewing user details such as **name**, **email**, **phone**.
---
## Steps to add user
1. Login as admin   - open the **lipa ada** system and sign in using your **Admin credentials**.
2. Navigate to **Manage Users**
3. Click on **Add User** this will open a new **user registration form**.
4. Fill in user details 
5. Assign user Role - if your system uses role based permissions, click **Manage Roles** 
 assign the new user the correct **role** or **permission**.
6. Save the user
   - Click **Add** the new user will appear in the user list automatically.
   - After adding confirm the user appears in the **user list** table , send login credentials to the user via email or SMS.
   - The user can now log in using the provided credentials.
![](manage users.PNG)
## search functionality
There is a **Search user** input box that allows the admin to quickly locate a user by typing their **Name**, **email**, or **Phone number**.

## + Add User
The **Add user** button opens a form where the admin can register a new user by providing :
**Name** , **Email** , **Phone** and **Role (e.g , Teacher, Admin , Stuff)**.

## Manage Roles
The **Manage Roles** button allows the admin to define or update user role and permissions.
example roles: (**Admin**, **Teacher**, **Accountant**, **Student**).
---
## Entity Setting
### General Settings
The **General Settings** section in **Lipa Ada** allows administrators to configure key system-wide preferences.  
These settings control how academic years, terms, accounting features, and branding elements behave across the Lipa Ada.
---
## Steps to configure general setting
1. Login as **Admin**.
2. Navigate to **Entity Settings** then **General Setting**.
3. Edit general information e.g **Active Academic Year**, **Active Term**, **Allow multiple fee structure** and so on.
4. Click **Update Settings** to save changes.

![](Genaral setting enty.PNG)

#### Academic Setting
The **Academic Settings** section in **Lipa Ada** allows administrators to configure all academic-related parameters for the school.  
It includes term management, academic section customization, section head assignments, and digital signature uploads.
---
![](academic setting.PNG)

## Step-by-Step Configuration Guide
### Accessing Academic Settings
1. Log in to **Lipa Ada** as an Administrator.
2. Navigate to **Admin Settings** from the sidebar menu.
3. Click on the **Academic Settings** tab at the top of the settings panel.  
   You will see sections for **Terms Management**, **Academic Section Colors**, **Section Head Assignments**, and **Digital Signatures**.
---
###  Configuring Terms Management

This defines the school calendar for each term (Term 1 to Term 4).

 **Start Date** The date when the term begins (format: `yyyy-mm-dd`). 
 **End Date** The date when the term ends (format: `yyyy-mm-dd`). 
 **School Days** Total number of school days within that term.
**Steps:**
1. Locate **Term 1**, **Term 2**, **Term 3**, and **Term 4** panels.
2. Enter the start and end dates for each term.
3. Fill in the number of school days (optional but recommended).
4. Verify that the dates do not overlap between terms.

![](academic setting 2_2.PNG)

###  Setting Academic Section Colors

Each academic level (Nursery, Primary, Secondary, Advance) can have a unique color for easy identification.
**Secondary Color** Theme color for the Secondary level. 
**Primary Color** Theme color for the Primary level. 
**Nursery Color** Theme color for the Nursery level. 
**Advance Color** Theme color for the Advanced level. 

**Steps:**
1. Click inside the color box beside each field.
2. Select your desired color using the color picker.
3. Use consistent colors that match your institution’s branding

### Assigning Section Heads

Assign users to manage specific academic sections.  
These users will be responsible for reports, approvals, and section-level management.
 **Head of Secondary** Selects the staff member overseeing Secondary. 
 **Head of Primary** Assigns the Primary section head. 
 **Head of Nursery** Assigns the Nursery section head.
 **Head of Advance** Assigns the Advance section head. 

**Steps:**
1. Click the dropdown beside each field.
2. Choose the user from the available staff list.
3. Ensure that the user has proper permissions assigned.

---

### Uploading Digital Signatures

Digital signatures are used for report cards and certificates.

 **Secondary Head Signature** Upload a signature image for the Secondary Head. 
 **Primary Head Signature** Upload a signature image for the Primary Head. 
 **Nursery Head Signature** Upload a signature image for the Nursery Head. 
 **Advance Head Signature** Upload a signature image for the Advance Head. 

**Steps:**
1. Click **“Choose File”** beside each signature field.
2. Select an image file (`.png`, `.jpg`, `.jpeg`).
3. Confirm that the uploaded signature matches the assigned section head.

---

### Saving Academic Settings

After configuring all fields:
1. Review your inputs for accuracy.
2. Click the **“Update Academic Settings”** button at the bottom.
3. A confirmation message should appear once the settings are saved successfully.

>  **Note:** Any changes here will immediately affect the academic calendar, report generation, and student management features.

---
### Message Templates
The **Message Templates** section in **Lipa Ada** allows administrators to create, manage, and configure pre-defined SMS and Email templates.  
These templates are used for automated notifications such as fee reminders,application confirmation, interview passed or failed, and payment confirm.

---
![](message template.PNG)

## steps to access
To access:
1. Log in to **Lipa Ada** as an Administrator.
2. Navigate to **Admin Settings**.
3. Click the **Message Templates** tab beside *General Settings* and *Academic Settings*.

---
##  Configuring a Message Template

**Steps:**
1. Go to **Admin Settings → Message Templates**.
2. Click **Add New Template** (or select an existing one to edit).
3. Fill in the following fields:
    - **Message Type** (SMS / Email)
    - **Message Body or content** (add text and placeholders as needed)

4. Click **Save Template** to store your configuration.

## Bio Devices

The **Bio Device** section in **Lipa Ada** allows administrators to manage biometric devices (such as fingerprint or RFID scanners) used for student and staff attendance tracking.  
This module integrates biometric hardware with the system to automatically record attendance and synchronize logs in real-time.
---
![](bio devices.PNG)
## steps to view devices
1. Log in to **Lipa Ada** as an Administrator.
2. Navigate to **Admin Settings** → **Bio Device** tab.
3. View or add biometric devices used across the school’s departments or campuses.
---
##  How to Add  Bio Device

![](add devices.PNG)
**Steps:**

1. Go to **Admin Settings → Bio Device**.
2. Click **Add Device** button.
3. Fill in the form fields:
    - **Device Name:** Enter a descriptive name (e.g., *Gate 1 Scanner*).
    - **Serial Number:** Input the serial number printed on the biometric device.
    - **Description** give short description for the devices.
    - **Status:** Choose **ON** to enable the device.
4. Click ** Add Device** to register it.
5. Once added, the device will appear in the list of configured bio devices.

## Synchronizing Devices
After adding a device:
- Click **Sync** to ensure communication between **Lipa Ada** and the device is working.
- The system will attempt to connect using the provided IP and port.
- If successful, logs will automatically sync with attendance data in real-time.
---

## Device Integration Notes

- Ensure the biometric device is connected to the **same local network** as the Lipa Ada server.
- The device time must be synchronized with the system clock to prevent mismatched attendance records.
- Regularly check connection status for uninterrupted data capture.
- Some devices may require **SDK configuration** or **firmware setup** before integration.
---

## User Activity
The **User Activity** section in **Lipa Ada** allows administrators to monitor, track, and audit user actions across the entire system.  
It provides visibility into all activities performed by system users, helping maintain accountability and security.
![](user activity.PNG)
---
## To access user activity:
1. Log in to **Lipa Ada** as an Administrator.
2. Go to **Admin Settings** → **User Activity** tab.
3. The page will display a searchable and filterable activity log for all users.
---

##  How to View User Activity

**Steps:**
1. Go to **Admin Settings → User Activity**.
2. A table will load showing all user actions recorded in the system.
3. Use **filters** to narrow results by:
    - **username or ID**
    - **Log Type**
    - **Table**
    - **Date Range**

4. Click on a show to view detailed activity information if available.
5. Click **Delete** button to activity.




---



 
