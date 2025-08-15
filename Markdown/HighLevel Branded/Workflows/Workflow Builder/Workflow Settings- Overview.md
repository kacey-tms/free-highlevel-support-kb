**Date Updated:** 2025-03-24T14:34:02.000Z

This article explores the Workflow Settings panel inside HighLevel's marketing automation tool. You'll learn what each setting does, how to configure it, and when to use it to improve message timing, contact experience, and automation logic. Whether you're managing a global audience or fine-tuning lead responses, these settings help automate smarter.

---

**TABLE OF CONTENTS**

* [What is Workflow Settings](#%E2%80%8B%E2%80%8BWhat-is-Workflow-Settings)
* [Key Benefits of Using Workflow Settings Effectively](#Key-Benefits-of-Using-Workflow-Settings-Effectively)
* [Overview of the Workflow Settings Panel ](#Overview-of-the-Workflow-Settings-Panel%C2%A0)
* [Best Practices for Configuring Workflow Settings](#Best-Practices-for-Configuring-Workflow-Settings)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What is Workflow Settings**

  
Workflow Settings in HighLevel control how automation behaves beyond the workflow steps. They allow you to fine-tune message timing, contact re-entry, and how responses are handled. These settings give you control over delivery accuracy, avoid message clutter, and improve automation logic to fit various business models.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155002174346/original/91PYZAJEFmNg1__pjW2r2GFt_TTBckF6BQ.gif?1688391108)

---

## **Key Benefits of Using Workflow Settings Effectively**

  
* **Timed Delivery for Better Engagement:** Leverage Time Window and Timezone settings to send messages when contacts are most likely to engage.
* **Smarter Automation Logic:** Use Stop on Response and Re-entry controls to prevent repetitive or irrelevant communication.
* **Clean and Organized Conversations:** Mark messages as read automatically to keep your Conversations tab focused and manageable.
* **Consistent Sender Identity:** Set default Sender Email and Name to ensure brand consistency and improve deliverability.
* **Personalization at Scale:** Apply timezone-based logic to adapt messaging for both local and global audiences.

---

## **Overview of the Workflow Settings Panel** 

  
This section gives you a visual and functional breakdown of the Workflow Settings panel. Understanding what each setting controls will help you build smarter automations, improve message timing, and better manage contact behavior throughout your workflows.

  
### **Accessing Workflow Settings**

  
To access Workflow Settings, open any workflow and click the Settings tab at the top.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155043819573/original/5wtwSqTTdIVjTBWDAjXt9CShFaBXwNfu6w.png?1742805747)

  
### **Contact Settings** 

  
The Contact Settings section controls how individual contacts behave within a workflow—specifically how they enter, re-enter, and exit the workflow based on their engagement. These settings are crucial when you’re managing automation logic that may apply to the same contact multiple times or where follow-up depends on user action.

  
* **Allow Re-Entry:** This toggle allows a contact to re-enter the workflow after they have already completed or been removed from it. If a contact is still active inside the workflow and the entry trigger fires again, they won’t be re-enrolled. However, once they’ve exited, enabling this option allows them to go through the same workflow again. This is useful for recurring campaigns such as annual renewal reminders or re-engagement sequences. **Note:** If your workflow uses appointment or invoice-based triggers, re-entry is permitted regardless of this setting.
* **Allow Multiple Opportunities:** When this option is enabled, a single contact with multiple opportunities can enter the workflow more than once—once for each opportunity. Each opportunity will be treated as a separate instance, meaning the same contact can have multiple parallel executions of the workflow. This is especially helpful in sales or pipeline-based workflows where the same lead may pursue multiple products or services independently.
* **Stop on Response:** This toggle ends the workflow for a contact as soon as they respond to any message sent from the workflow (email, SMS, or other supported channels). It’s ideal for conversational or sales-focused automations where you want to stop further automated steps once a user shows engagement by replying. This helps avoid overwhelming your contacts with additional follow-ups after they’ve already responded.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155043819277/original/NNFYBQ3io2oMFT_nA2KxFkRAlMqZH1l9oQ.jpeg?1742805522)

  
### **Communication Settings**

  
The Communication Settings section controls how and when your workflow sends messages, as well as how they appear to contacts. It’s designed to optimize delivery timing, support personalized outreach, and ensure consistency in your sender identity across emails and SMS.

  
### **Timezone**

  
This dropdown allows you to choose how time-based actions like Wait steps and Time Windows are executed:

  
* **Account Timezone:** All time-based actions follow your account’s default timezone.
* **Contact Timezone (not shown in this screenshot but available):** Time-based actions are executed according to the individual contact’s timezone. This is especially useful for global audiences.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155043821314/original/gOl09AFdYeU_7HGhLl-BrD2WR5zy5KlvtA.png?1742806886)

  
### **Time Window (Specific Time)**

  
This toggle restricts workflow actions (like sending emails or SMS) to a specific time range. When Specific Time is enabled, you define the hours during which actions are allowed. Any action that falls outside that range is delayed until the next available window. This helps ensure communications are sent when recipients are most likely to engage—for example, during business hours.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155043821005/original/0Y2v2TIzK6qClacO-T6qOPXfSzkZ5Mi8kQ.png?1742806719)

  
### **Sender Details (From Name and From Email)**

  
Here you can set a default From Name and From Email that will be used in all email actions within the workflow. This ensures consistency in branding and helps with email deliverability. These defaults can still be overridden in individual email steps if needed.

  
**Custom Values:** You can also use custom values in the From Name and From Email fields by clicking the tag icon. This allows you to dynamically insert information—such as the assigned user’s name or email—making it easy to personalize sender details across workflows. It’s especially helpful in team-based environments where emails should appear to come from the contact’s assigned rep or account manager.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155043820904/original/b9KZbRdsXF7SX4KDf_iP9hLUjib2E1cWvw.png?1742806658)

  
### **From Number**

  
This dropdown allows you to select a default number from which all SMS messages in the workflow will be sent. If your account has multiple phone numbers, this ensures the workflow consistently uses the same sender identity across all messages.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155043820859/original/0GenAOnIqyJJ-sbw4UA0yzpsHyK9lrI9yA.png?1742806622)

  
### **Mark as Read (Conversations)**

  
When enabled, this toggle automatically marks messages sent from the workflow as “read” in the Conversations tab. By default, automated messages appear as unread. Turning this on helps keep your inbox organized, especially in high-volume workflows where unread message count can quickly build up.

  
[![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155043820789/original/OagX1NHSwTotqk6rOMajs1WyuQTnyRNvlA.png?1742806601)](https://help.gohighlevel.com/a/solutions/articles/48001239875/edit?portalId=48000045315)

---

## **Best Practices for Configuring Workflow Settings**

  
* Use Contact Timezone for campaigns with global users to send messages at relevant times.
* Enable Allow Re-Entry for recurring workflows like renewals or onboarding updates.
* Use Stop on Response for sales and support flows to pause automations once the user replies.
* Always verify your Sender Email to improve email inbox placement and avoid delivery issues.
* Avoid Specific Time for urgent workflows where timing flexibility is important.

---

## **Frequently Asked Questions**

  
**Q: Can Workflow Settings override specific actions in the workflow?**

No. Workflow Settings apply at the workflow level, but some steps (like email) can override defaults.

  
**Q: What happens to existing contacts if I change the Timezone or Time Window?**

Changes only apply to new contacts entering the workflow. Existing contacts retain prior settings.

  
**Q: Can a contact re-enter multiple times with Allow Re-Entry enabled?**

Yes, if they’re no longer active in the workflow and the trigger condition is met again.

  
**Q: Does Stop on Response work if the contact replies to a previous unrelated message?**

No, the contact must reply to a message sent specifically from the workflow.

  
**Q: How can I test Workflow Settings before going live?**

Use test contacts in various timezones and monitor their path through Enrollment History and Execution Logs.