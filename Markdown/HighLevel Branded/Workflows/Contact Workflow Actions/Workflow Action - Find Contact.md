**Date Updated:** 2025-07-26T03:29:06.000Z

The workflow action Find Contact allows you to pull a contact into a workflow based on search criteria like email. It also handles the case where no matching contact is found.

---

**TABLE OF CONTENTS**

* [What is Find Contact Workflow Action](#What-is-Find-Contact-Workflow-Action)
* [Key Benefits of Find Contact Workflow Action](#Key-Benefits-of-Find-Contact-Workflow-Action)
* [Configuring the "Find Contact" Workflow Action](#Configuring-the-)  
   * [Name Your Action](#Name-Your-Action)  
   * [Select Fields](#Select-Fields)  
   * [Standard Fields](#Standard-Fields)  
   * [Custom Fields](#Custom-Fields)
* [Use Cases](#Use-Cases)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What is Find Contact Workflow Action**

  
The Find Contact workflow action enables you to **identify a contact** in your database using specified criteria, such as standard or custom fields. This action is perfect for workflows that are **triggered without a contact already specified**, but do have other **identifying information** such as an email.

  
Normally, this action is used when the workflow is triggered by a trigger that does not already have a contact attached to it. For example, when the trigger is Inbound Webhook it will have a payload of one or more query parameters. If the queryParams do not include a user ID, but do include an email, or other identifying information, then the Find Contact action can be used to turn the email into a user ID so that actions can be run on that contact.

---

## **Key Benefits of Find Contact Workflow Action**

  
* **Enhanced Workflow Efficiency:** Automates the contact search process, saving time and reducing manual errors.
* **Flexible Search Capabilities:** Supports standard and custom fields, allowing precise and tailored contact searches.
* **Contactless Integration:** Specifically designed for workflows triggered by a contactless triggers such as **Inbound Webhoo** **k**
* **Advanced Matching:** Includes external reference matching, enabling searches based on custom identifiers like “Stripe Customer ID.”
* **Improved Customer Engagement:** Ensures accurate targeting for communications and follow-ups, enhancing customer interactions.
* **Branching Support:** Automatically creates distinct paths in your workflow based on whether a contact is found or not, enabling tailored actions for each scenario.

---

## **Configuring the "Find Contact" Workflow Action**

  
Follow these steps to configure the "Find Contact" action in your workflow.  
  
  
### **Access Workflow Settings**

  
Navigate to the workflow builder inside **"Automation"** section in your CRM. Create a new workflow from scratch or select the existing workflow where you want to implement the **"Find Contact"** workflow action.

### 

### **Add a New Action**

  
Click **“+”** icon and select **"Find Contact"** action from the dropdown menu.

  
### **![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039249538/original/QeM8v2EHcsAv9Pjb6KYgMm5jB1HlsXax2Q.png?1735920178)**  

### **Name Your Action**

  
Provide a descriptive name, such as **“Find Contact by Email.”**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039249578/original/F7sI1DcqMK1NL5qk-dvd3J0ozCIbDQBbvw.png?1735920212)

  
---

### **Selecting Standard Fields**

  
Options include First Name, Last Name, Email, Phone, and more.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039249673/original/gK9muzOm9tJ3EK88Yjkl3w_y2OPGHe9Qxg.png?1735920304)

  
### **Selecting Custom Fields (optional)**

  
If you haven't already created the custom field, Add unique fields such as “Customer ID” or “Subscription Tier.” If you have them already, Just scroll down to find the Custom Fields you have created within the system.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039249651/original/6ihylo4OdVHg-gBuJXxczL-wmQr2jSGGeg.png?1735920282)

  
### **Configure Triggers**

  
Pair the action with triggers like **"Inbound Webhook"** to activate it dynamically.

---

### **Test and Save**

  
Validate the configuration using test data to ensure accuracy. **Save** the action once the setup is complete.
  
  
### **Publish the Workflow**

  
Enable the workflow to automate the contact search process effectively.

---

## **Frequently Asked Questions**

**Q. What happens if the contact is not found?**

Once the Find Contact action is configured it creates a branch, one for "contact found" and one for "contact not found". You can create whichever actions are appropriate on the "contact not found" branch.  
  
**Q. How does external reference matching work?**

You can store external identifiers, such as a **“Stripe Customer ID,”** in a custom field. The Find Contact action uses this field to locate the corresponding contact in the CRM.
  
  
**Q. Can I combine this action with other workflow actions?**

Absolutely. The Find Contact action can be paired with other actions like **“Send Email”** or **“Update Contact”** to create complex workflows.
  
  
**Q. Can I use multiple fields for the search?**

Yes, you can configure multiple fields to refine the search criteria. All specified field values must match for the action to locate the contact (ex: this AND this AND this).

  
**Q. Can I use other triggers?**

In addition to the Inbound Webhook trigger you can pass the necessary merge fields in through a custom App Marketplace trigger (these are Premium triggers created by 3rd party developers to support their App Marketplace apps).