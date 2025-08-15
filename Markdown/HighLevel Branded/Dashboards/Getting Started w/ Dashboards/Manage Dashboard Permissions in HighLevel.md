**Date Updated:** 2025-06-10T02:10:57.000Z

Dashboards can be private to their creator, or they can be shared with different roles at different access levels.

---

**TABLE OF CONTENTS**

* [What Are Dashboard Permissions?](#What-Are-Dashboard-Permissions?)
* [Manage Dashboard Permissions](#Manage-Dashboard-Permissions)  
   * [Set Permissions On A New Dashboard](#Set-Permissions-On-A-New-Dashboard)  
         * [Step 1: Add A Dashboard](#Step-1%3A-Add-A-Dashboard)  
         * [Step 2: Select Blank Dashboard](#Step-2%3A-Select-Blank-Dashboard)  
         * [Step 3: Set Permissions and Save](#Step-3%3A-Set-Permissions-and-Save)  
   * [Set Permissions On An Existing Dashboard](#Set-Permissions-On-An-Existing-Dashboard)  
         * [Step 1: Action Manage Permissions](#Step-1%3A-Action-Manage-Permissions)  
         * [Step 2: Set Permissions and Save](#Step-2%3A-Set-Permissions-and-Save)  
   * [Agency vs Account Views](#Agency-vs-Account-Views)  
         * [Agency View Of Dashboard Permissions](#Agency-View-Of-Dashboard-Permissions)  
         * [Account View Of Dashboard Permissions](#Account-View-Of-Dashboard-Permissions)  
   * [Roles and Permissions Hierarchy](#Roles-and-Permissions-Hierarchy)
* [What's Next:](#What's-Next%3A)

---

# **What Are Dashboard Permissions?**

  
Dashboards offer the following levels of permissions:

  
| **Level** | **Description**                                                                                                  |
| --------- | ---------------------------------------------------------------------------------------------------------------- |
| FULL      | Gives the person the ability to create, edit, share, and delete Dashboards                                       |
| EDIT      | Gives the person the ability to edit a dashboard and the widgets. The person isn't able to delete the dashboard. |
| VIEW      | Gives the person read-only access to a Dashboard                                                                 |
| NO ACCESS | Restricts access to the dashboard entirely                                                                       |

  
Here are how different actions on dashboards work for different level of permissions

  
| | **FULL**                                           | **EDIT** | **VIEW** | **NO ACCESS** | **PRIVATE DASHBOARD** | **OWNER** |   |
| ---------------------------------------------------- | -------- | -------- | ------------- | --------------------- | --------- | - |
| Manage Permissions                                   | ✅        | ❌        | ❌             | ❌                     | ❌         | ✅ |
| Delete Dashboard                                     | ✅        | ❌        | ❌             | ❌                     | ❌         | ✅ |
| Set as Default Dashboard                             | ✅        | ❌        | ❌             | ❌                     | ❌         | ✅ |
| Edit Dashboard                                       | ✅        | ✅        | ❌             | ❌                     | ❌         | ✅ |
| Clone Dashboard                                      | ✅        | ✅        | ❌             | ❌                     | ❌         | ✅ |
| View Dashboard                                       | ✅        | ✅        | ✅             | ❌                     | ❌         | ✅ |
| Duplicate to another Sub-Account (Only Agency Level) | ✅        | ✅        | ✅             | ❌                     | ❌         | ✅ |
  
  
Only dashboard Owners or roles with Full permission are able to edit a dashboard's permissions.
Agency Admins always have Full access to all non-private dashboards.
Only Account Admin or Agency roles with full access to a dashboard are able to set it as a default dashboard.  
Only Agency roles are able to duplicate a dashboard to another subaccount.

---

# **Manage Dashboard Permissions**

  
## **Set Permissions On A New Dashboard**

  
### **Step 1: Add A Dashboard**

  
Navigate to Dashboard, click on the Dashboard Selection menu (blue), then click on Add Dashboard.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044433881/original/rQJh1RSrr244FcvqH8VsYlSNaL1_5L9_6A.png?1743641657)
  
  
### **Step 2: Select Blank Dashboard**

  
Under Create a Blank Dashboard, click Select.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044433890/original/lpbrI6m-ixLatlPsrrpGNDCwvkylimB_Fw.png?1743641724)
  
  
### **Step 3: Set Permissions and Save**

  
On the New Dashboard modal, leave the dashboard private, or turn that off to access sharing permissions. When you are happy with the settings, click Confirm to create the new dashboard with those permissions.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044433908/original/9V9Sr9PLG29YqUu0VXW1O2t2yRRyqmHvdQ.png?1743641801)
  
  
## **Set Permissions On An Existing Dashboard**

  
### **Step 1: Action Manage Permissions**

  
On your existing dashboard, click the 3-dot "action menu", then click Manage Permissions.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044433750/original/XBQjE4b9QWgmSCGpAV3ShVjvdPCuPizE5g.png?1743641029)
  
  
### **Step 2: Set Permissions and Save**

  
Use the Private toggle to switch between private (only yourself) or sharing permissions.

  
When you are satisfied with your permissions changes, click Save to close the modal and return to the dashboard.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044433989/original/whua1cN1ou81Jrr3_UI7SGEnO-PPebUdng.png?1743642044)

---

## **Agency vs Account Views**

  
Permissions screen and options changes as per the role of the logged in user

  
### **Agency View Of Dashboard Permissions**

  
Agency Admins will always have full access to all dashboards except those marked private by their creator. In the Agency view, there are **three** roles with access settings: **Agency User,** Account Admin, and Account User.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044434191/original/ag_owqTRkCZiAF5mHoJ3MUHYMr0kLRkY-g.png?1743643164)  

  
### **Account View Of Dashboard Permissions**

  
In the Account view there are **two** roles with access settings: Account Admin and Account User. 

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155023290478/original/LNohQGZJfVvUZVBvP4IWBFbbhDDct6fjHA.png?1711017852)

  
---

## **Roles and Permissions Hierarchy**

  
Dashboard Permissions follow a clear hierarchy to ensure smooth management of access levels:

  
Agency Admins > Agency Users > Account Admins > Account Users.

  
Permissions for higher-level roles will override permissions for lower-level roles. Lower-level roles cannot posess higher permissions than higher-level roles.

  
For example, if a dashboard is set to Account Admin:Edit and Account User:Edit is changed to Account Admin:View, then Account User will be automatically changed to View as well. 

---

# **Frequently Asked Questions**

  
**Q: What happens if no permissions are set?**  
By default, dashboards are visible to all users unless restricted.

  
**Q: What does "Only Assigned Data" restrict exactly?**  
It filters dashboard widgets to only show data related to the user's assigned records (contacts, opportunities, etc.).

  
**Q: How do I remove a user or role from a dashboard?**  
Re-open the permissions modal for the dashboard and uncheck the user or role.

---

# **Related Articles**

  
* [How to Edit a dashboard](https://help.gohighlevel.com/en/support/solutions/articles/155000001536)
* [How to clone a dashboard (in the same location)](https://help.gohighlevel.com/en/support/solutions/articles/155000001534)
* [How to pin dashboards as favourite](https://help.gohighlevel.com/en/support/solutions/articles/155000001535)