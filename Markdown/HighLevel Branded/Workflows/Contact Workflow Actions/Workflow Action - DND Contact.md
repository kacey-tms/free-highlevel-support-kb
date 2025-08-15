**Date Updated:** 2024-09-02T15:16:20.000Z

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Action Name](#Action-Name)
* [Action Description](#Action-Description)
* [Action Details](#Action-Details)
* [Example](#Example)

##   

## Overview

The "**DND Contact**" action allows you to manage the Do-Not-Disturb (DND) settings for a contact. This action can enable or disable DND across all communication channels or specific ones. It’s useful for ensuring that contacts are not disturbed by automated messages when they have requested not to be contacted.

  
## Action Name

**DND Contact**

  
## Action Description

The "DND Contact" action provides options to:

1. Enable DND for all channels.
2. Enable DND for specific channels.
3. Disable DND for all channels.
4. Disable DND for specific channels.

By using this action, you can control the flow of communication based on the preferences or requirements of your contacts.

  
## Action Details

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155032057519/original/ccfN0F513a9XKNHYHa2bJlZkR397BBEuqQ.png?1725269343)

  
| Field Name             | Description                                                                                                   | Mandatory |
| ---------------------- | ------------------------------------------------------------------------------------------------------------- | --------- |
| Mark as Read or Unread | Choose to mark the conversation as either read or unread. Options include: None. Mark as Read. Mark as Unread | No        |

##   

#### **How to Configure**

1. **Action Name:** Enter a name for this action, such as "Enable DND for All Channels."
2. **DND:** Choose from the dropdown menu to either enable or disable DND, and specify whether it applies to all channels or only specific ones.

####   

#### **Some Triggers which can be used with the action (But not limited to)**

* **Appointment Status Changed:**  
   * **Trigger:** Use the "Appointment Status Changed" trigger.  
   * **Configuration:** Set a filter for the appointment status to be "Completed" or "Showed" (depending on the terminology used in your system).  
   * **Action:** Add the "DND Contact" action to disable DND, indicating that the contact can now receive communications.
* **Appointment Scheduled:**  
   * **Trigger:** Use the "Appointment Scheduled" trigger.  
   * **Configuration:** Add a condition to wait for a specific period after the appointment time (e.g., 1 hour after the scheduled end time).  
   * **Action:** After the waiting period, add the "DND Contact" action to disable DND, assuming the appointment has been completed.
* **Task Completed:**  
   * **Trigger:** Use the "Task Completed" trigger associated with appointment follow-up tasks.  
   * **Configuration:** Link the task to follow-up actions post-appointment, such as sending a thank you email or a survey.  
   * **Action:** Once the task is marked as completed, add the "DND Contact" action to disable DND, allowing communication to resume.
* **Custom Field Update:**  
   * **Trigger:** Use a "Custom Field Update" trigger where a field is updated to indicate the appointment's completion.  
   * **Configuration:** Create a custom field that is marked when the appointment is considered completed (manually or via another process).  
   * **Action:** When this field is updated, use the "DND Contact" action to disable DND.
* **Manual Trigger via Internal Notification:**  
   * **Trigger:** Set up a process where team members manually update a contact's record or status after verifying appointment completion.  
   * **Configuration:** Use an internal notification or task completion as a trigger.  
   * **Action:** Use the "DND Contact" action to disable DND for the contact.

##   

## Example

**Scenario:** A customer has opted out of receiving promotional SMS but wants to stay updated via email.

1. Set up a workflow trigger when a contact opts out of SMS communication.
2. Add the "DND Contact" action.
3. Configure it to enable DND for SMS only while keeping other channels active.
4. This setup ensures the contact will not receive SMS notifications but can still receive updates via email or other preferred channels.

This approach respects customer preferences and helps maintain a positive relationship by avoiding unwanted communications.