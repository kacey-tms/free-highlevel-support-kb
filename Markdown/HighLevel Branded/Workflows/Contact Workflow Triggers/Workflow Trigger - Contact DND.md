**Date Updated:** 2025-01-20T04:51:15.000Z

This article provides an in-depth guide on the **"Contact DND"** Workflow Trigger in HighLevel, explaining its purpose, key benefits, and how to set it up effectively. You’ll also find step-by-step configuration instructions, practical use cases, and answers to common questions about this feature.

---

**TABLE OF CONTENTS**

* [What is Contact DND Workflow Trigger?](#What-is-Contact-DND-Workflow-Trigger?)
* [Key Benefits of Contact DND Workflow Trigger](#Key-Benefits-of-Contact-DND-Workflow-Trigger)
* [Configuring the Contact DND Workflow Trigger](#Configuring-the-Contact-DND-Workflow-Trigger)  
   * [Name Your Workflow Trigger](#Name-Your-Workflow-Trigger)  
   * [Setting Up Filters (Optional)](#Setting-Up-Filters-%28Optional%29)  
         * [Select DND Flag](#Select-DND-Flag)  
         * [Choose Specific Channels](#Choose-Specific-Channels)
* [Use Cases](#Use-Cases)  
   * [Managing Opt-Outs for Marketing Campaigns](#Managing-Opt-Outs-for-Marketing-Campaigns)  
         * [Trigger Setup:](#Trigger-Setup%3A)  
         * [Workflow Actions:](#Workflow-Actions%3A)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What is Contact DND Workflow Trigger?**

  
The Contact DND (Do Not Disturb) trigger activates a workflow whenever a contact’s DND status changes. This trigger helps businesses manage communication preferences by ensuring that contacts who choose not to be disturbed are automatically excluded from certain actions and campaigns. It can be applied when DND is enabled or disabled, offering granular control over different communication channels such as email, SMS, and calls.

---

## **Key Benefits of Contact DND Workflow Trigger**

  
This section explains how this trigger helps businesses manage customer communication preferences effectively, ensuring compliance and improving customer trust.

  
* **Respect Communication Preferences:** Automatically exclude contacts who have opted out of certain types of communication, ensuring compliance with privacy regulations.
* **Improved Automation Efficiency:** Simplifies workflows by enabling or disabling communication based on DND status.
* **Customizable Channel Control:** Allows businesses to manage DND settings per channel (email, SMS, calls) or apply them globally across all channels.
* **Enhanced Customer Satisfaction:** Reduces unwanted contact, leading to a better customer experience and higher trust.
* **Streamlined Compliance Management:** Helps businesses remain compliant with communication laws and guidelines by automating opt-outs for SMS and email.

---

## **Configuring the Contact DND Workflow Trigger**

  
In this section, you will learn how to select the trigger, configure specific filters such as DND status and channels, and define precise actions based on customer opt-out preferences. Properly setting up these filters ensures that the workflow activates only under the correct conditions, such as when DND is enabled or disabled, or for specific communication channels.
  
  
### **Navigate to Workflow Builder**

  
Head over to the **"Automation"** section of the CRM platform and select **“+ Create New Workflow.”** Choose **“Start from Scratch”** to build a workflow from the ground up or **“Select a Template”** to customize pre-built options available in the system. For those who wish to add this trigger to an existing workflow, locate the desired workflow, hover over it, and select it to begin editing..

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040037367/original/z_k0SVZobMFkDE043ARVCJY0V2GRGAn6zw.png?1737130239)
  
  
### **Add a New Workflow Trigger**

  
To start setting up the “Contact DND Workflow Trigger,” click the **“Add New Trigger”** button and search for **“Contact DND”** in the list of available options. This ensures the workflow activates whenever a contact’s DND status changes.

###   

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040037390/original/D4VBjjC2XCXrp9yHP6U1SCpn7oj_xlW4xA.png?1737130279)
  
  
### **Name Your Workflow Trigger**

  
Assign a descriptive name to your trigger for easy identification. A clear name ensures that your workflows remain organized and simplifies locating specific triggers for future updates. In this example, we have named our trigger as “DND for WhatsApp.”

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040037444/original/L01Jn-C5PPGGhsEAh0LHvtARugFfgHZ5cw.png?1737130324)

  
### **Setting Up Filters (Optional)**

  
Setting up filter ensures the workflow activates based on specific conditions related to a contact’s Do Not Disturb (DND) preferences. Here’s how you can configure each filter.

  
#### **Select DND Flag**

  
The DND Flag filter allows you to precisely control when the workflow should trigger based on the Do Not Disturb (DND) preferences of your contacts. You can configure this filter to activate the workflow for specific DND scenarios, such as when DND is enabled or disabled across all communication channels or limited to specific channels like email, SMS, or calls.  
  
* **Disabled DND for All Channels:** This option triggers the workflow when the DND status is turned off for all communication channels (e.g., email, SMS, phone calls). It is useful when you want to resume communications with a contact who has opted back in for all channels.
* **Disabled DND for Specific Channels:** This triggers the workflow when DND is turned off for specific channels only (e.g., just SMS or email). It allows you to re-engage with contacts who have chosen to receive communications through certain channels but still prefer to avoid others.
* **Enabled DND for All Channels:** This option activates the workflow when the contact has opted out of communications on all channels, such as email, SMS, phone calls, and more. This ensures no communications are sent to contacts who prefer complete disconnection.
* **Enabled DND for Specific Channels:** This triggers the workflow when DND is enabled for one or more specific channels (e.g., SMS or calls). It ensures communications are blocked only through the selected channels while still allowing engagement through others, such as email.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040037532/original/VeCaRwawkqpse0fzo681Qos52X3aIaPQsg.png?1737130429)

  
#### **Choose Specific Channels**

  
This option refines the trigger to target specific communication channels where DND is enabled or disabled. Know that you can only configure this filter after selecting **“Specific Channel”** option in the DND Status filter (see previous step).

  
* SMS
* Email
* Phone Calls
* Google My Business (GMB) Messages
* Facebook Messages

###   

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040037610/original/t2gtnkTfOQ2-JSkzsz1g4HjUMvt7iNbOOA.png?1737130548)

  
### **Save and Publish the Workflow**

  
Saving your progress while building a workflow is crucial to ensure you don’t lose your adjustments and can pick up right where you left off. Additionally, once your workflow is complete and ready to function, don’t forget to toggle it from **“Draft”** to **“Publish”** to activate it.

---

## **Use Cases**

  
### **Managing Opt-Outs for Marketing Campaigns**

  
**Scenario:** A business runs multiple marketing campaigns through email and SMS. Some contacts opt out of SMS communication but remain interested in receiving emails. The business wants to ensure that such preferences are respected in all future campaigns.

  
#### **Trigger Setup:**

* **Trigger:** Contact DND
* **Name:** SMS Opt-Out

  
**Filters:**

* **DND Flag Is:** Enabled for specific channels
* **DND Channel Is:** SMS

#### **Workflow Actions:**

* Add a tag “SMS Opt-Out” to the contact for reference. Use "Add Contact Tag" workflow action.
* Remove the contact from any ongoing SMS campaigns using the "Remove from Workflow" action.
* Notify the marketing team via an internal notification about the opt-out. Choose "Internal Notification" workflow action.

  
**Outcome:** This automation ensures that the contact is excluded from SMS communications while remaining part of email campaigns, respecting their preferences and enhancing customer satisfaction.

---

### **Re-enabling Communication for Opted-In Contacts**

  
**Scenario:** A contact who had previously opted out of all communications decides to opt back in. The business wants to automatically resume communication by removing any opt-out tags and notifying relevant teams.

**Trigger Setup:**

* **Trigger:** Contact DND
* **Trigger Name:** Re-enable Communication

  
**Filters:**

* **DND Flag Is:** Disabled DND for All Channels

  
**Workflow Actions:**

* Remove the tag “Do Not Contact” from the contact. Choose "Remove Contact Tag" workflow action.
* Notify the sales team via an internal notification. Choose "Internal Notification" workflow action.
* Resume the contact in relevant workflows by using the action named "Add to Workflow".

  
**Outcome:** The contact is re-integrated into marketing and sales workflows, ensuring they start receiving relevant communication immediately after opting back in.

---

## **Frequently Asked Questions**

  
**Q. How does the Contact DND trigger handle specific channels versus all channels?**

The trigger allows you to set DND for specific channels (such as SMS, email, or calls) or apply it globally across all channels. This flexibility helps businesses respect preferences without completely stopping communication when only one channel is opted out.
  
  
**Q. Can I use tags to manage DND preferences?**

Yes, you can add tags like “DND SMS” or “DND Email” to contacts. These tags can be referenced in other workflows to exclude contacts from specific actions or campaigns.
  
  
**Q. What happens if a contact is already in a workflow when their DND status changes?**

HighLevel automatically skips any communication steps in a workflow that conflict with the contact’s DND settings. For example, if a contact has DND enabled for email, the system will skip email steps but still process other actions like SMS or task creation.  
  
**Q. Should I remove contacts from all workflows when they enable DND?**

Not necessarily. HighLevel ensures compliance by skipping communication steps based on DND settings. However, if a contact opts out of all communication, you may choose to remove them from all workflows using the Remove from All Workflows action.
  
  
**Q. How do I ensure compliance for SMS and email communications?**

Enable the automated compliance settings under Business Profile in HighLevel. This ensures that opt-out messages and sender information are automatically added to SMS and emails, keeping your communications compliant.

  