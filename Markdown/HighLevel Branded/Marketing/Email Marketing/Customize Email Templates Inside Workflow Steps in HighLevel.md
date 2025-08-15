**Date Updated:** 2025-07-01T21:18:18.000Z

Learn how to use email templates inside workflows without accidentally changing the original template. This guide explains how template behavior works, how to safely customize email content within a workflow, and how to manage updates across multiple steps. By the end, you’ll be able to confidently manage email templates while minimizing risk and confusion.

---

**TABLE OF CONTENTS**

* [What is Email Templates in Workflow Steps](#%E2%80%8B%E2%80%8BWhat-is-Email-Templates-in-Workflow-Steps)
* [Key Benefits of Managing Email Templates in Workflow Steps](#Key-Benefits-of-Managing-Email-Templates-in-Workflow-Steps)
* [How to Customize Template Behavior in Workflow Emails](#How-to-Customize-Template-Behavior-in-Workflow-Emails)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What is Email Templates in Workflow Steps**

  
In HighLevel workflows, the “Send Email” action lets you add a saved email template to automate communication. While templates help standardize messaging, each workflow often needs small tweaks—like a different subject line or call-to-action.

  
When you add a template to a Send Email action, HighLevel creates a separate copy for that specific step. Any edits you make affect only that step, not the original template or other workflows. This ensures you can safely customize emails without risking unintended global changes.

---

## **Key Benefits of Managing Email Templates in Workflow Steps**

  
* **Safe Customization:** Edit emails directly in workflows without impacting the original template or other workflows.
* **Flexible Reuse:** Use the same template across workflows and adjust it contextually as needed.
* **Global Sync (When Needed):** Push updates from a template to selected workflow steps using a manual sync process.
* **Template Library Growth:** Save any customized workflow email as a new template for future use.
* **Reduced Risk:** Prevent unintended global changes during team collaboration or campaign edits.

---

## **How to Customize Template Behavior in Workflow Emails**

  
### **Open the Workflow Area**

  
Go to the **Automation** tab in the left menu and click on **Workflows** at the top. This is where you can view and manage the workflows where your email templates will be used.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049153002/original/1W0YnmzOEKt1lBpqC2QPwlZhn71A5PkuxQ.png?1751371071)
  
  
**Important:** Before you move on to the next step, make sure to set up a trigger and define the basic structure of your workflow. This ensures your automation is ready for configuration.
  
  
### **Add a Send Email Action**

  
In the workflow builder, click the **+** icon to add a new action. Under the **Communication** section, select **Send Email** to begin configuring your email step.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049153812/original/6ObjGzKad2KaNEiOr0TXxoWRHhjG6CJ09Q.png?1751371766)
  
  
**Note:** Before editing the email content, fill out the basic email settings like From Name, From Email, CC, and BCC as needed. These ensure proper sender details are applied when the email is sent.
  
  
### **Select an Email Template**

  
Use the **Templates** dropdown to select the email you want to use in this workflow step. This will create a separate copy of the template, allowing you to customize it without affecting the original.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049154588/original/HJ3RnLfYhkpF7LMz6q8kAX6owNHivPbfTA.png?1751372366)
  
  
### **Open the Template Editor**

  
Hover over the template preview to reveal the **Edit** button, then click it to open the email editor. This lets you customize the template specifically for this workflow step.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049154800/original/LHUtO0tCOaATumPzWlrJ1yicwcnpesrJHQ.gif?1751372494)
  
  
### **Overview of Email Editor Tools and Layout Options**

  
The email editor includes several tools that help you customize the structure, design, and content of your template. Understanding these interface sections will make it easier to create professional, responsive emails.

  
* **Template Title and Name Editing:** At the top-left, you can see the name of your email template. Click the pencil icon next to the title to rename the template. This helps you keep templates organized, especially when managing multiple versions or use cases.
* **Top Action Toolbar (Layout Controls):** The row of icons below the title allows you to manage the layout and structure of your email. The + icon opens layout blocks, stack icon manages layers, the T icon sets global text styles, and the paper icon handles template-level settings like width and padding. These tools give you foundational control over how your email is visually arranged.
* **Element Library (Drag-and-Drop Blocks):** The vertical panel on the left displays all available drag-and-drop content blocks. You can add text, images, buttons, logos, dividers, social links, videos, footers, product grids, countdown timers, and more. These elements allow you to build rich, visual emails tailored to your message and goals.
* **View Mode and Editing Options:** The section at the top-center lets you switch between editing and preview modes. You can also toggle between desktop, tablet, and mobile views to see how your email will appear on different devices. This is essential for ensuring responsive design.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049161754/original/SAN6AtusV4FYiv3RUgD_yMe0E5AQpu8DNA.png?1751376875)
  
  
### **Open the Subject Settings**

  
Click the **gear icon** in the top-right corner of the email editor to open the settings panel. This is where you’ll be able to access and modify the subject line for the email.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049159458/original/5M4GHVEkuykgZArrX3-fxw8Y-pQ0ckB6jA.png?1751375450)
  
  
### **Enter a New Subject Line**

  
In the settings panel that appears, locate the **Subject** field. Type in your desired subject line and click **Confirm** to apply the changes. This subject will be used when the email is sent through the workflow.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049159743/original/rEIosCz6vmyOUTEzNXlTJUbg9nwOpN4W0w.png?1751375634)
  
  
### **Save as New Template**

  
After customizing your email, click **Save as new Template** in the top-right corner to store it for future use. This creates a new version in your template library without altering the original.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049158790/original/KG7ARZ7wg-pG7PXF-woJUku-_WVVvYWw5A.png?1751374977)
  
  
### **Name the New Template**

  
After clicking **Save as new Template**, enter a name to identify your custom version. Click **Continue** to save it to your email template library for future use in other workflows.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049159290/original/3_1X2jdTrl5D5k13kQ4CcjqDwEZf56Jj6g.png?1751375300)
  
  
### **Save the Edited Email**

  
Click **Save** in the top-right corner to update the email within this workflow step. This saves your changes locally to the step only and does **not** create a new template in your email template library.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049159028/original/cEvISQgMGqmQ52aO4KxLE4zfnSabdNA-Pw.png?1751375132)
  
  
### **Send a Test Email to Review Your Customizations**

  
After editing your email template within the workflow, use the **Test Emails** field to enter one or more recipient addresses, then click **Send Test Mail**. This allows you to preview the customized email in an actual inbox and verify formatting, personalization, and design before saving the workflow action.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049173148/original/1p4EtvKqrejM63-2UUOScy84nndWop3pBw.png?1751384192)

---

## **Frequently Asked Questions**

  
**Q: Can I link a workflow email back to the original template after editing it?**

No. Once a template is copied into a workflow step and edited, it becomes independent. If you want to re-establish alignment with the original template, you must manually re-insert the template into that step or use the sync function.

  
**Q: Can I track which workflow steps are using a specific template?**

Yes. The Sync Changes tool in the Templates section shows a list of workflow steps that are currently linked to the selected template for syncing purposes. This helps with identifying where global updates will apply.

  
**Q: What happens if I edit a synced workflow email after applying a global update?**

Any manual changes you make after syncing will remain local to that workflow step. They will not affect the original template unless you save the edited version as a new template.

  
**Q: Is there a way to preview changes before syncing a template across multiple workflows?**

No. Syncing is a direct action that applies the current version of the template to the selected workflow steps. It’s recommended to review both the template and selected workflows before proceeding.

  
**Q: Can I prevent team members from editing certain workflow emails after inserting a template?**

There’s currently no lock or restriction on editing email actions within workflows. To manage this, consider documenting template usage policies or using role-based permissions to limit access.