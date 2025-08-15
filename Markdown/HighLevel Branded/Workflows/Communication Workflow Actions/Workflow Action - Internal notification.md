**Date Updated:** 2025-08-01T15:30:51.000Z

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Action Name](#Action-Name)
* [Action Description](#Action-Description)
* [Action Details](#Action-Details)
* [Example](#Example)

##   

## Overview

The Internal Notification Action enables to create and send notifications to specific users or teams within your organization. These notifications are triggered by specific events or conditions defined in workflows, ensuring that your team stays informed about important activities and tasks.

  
## Action Name

  
Internal Notification

  
## Action Description

The Internal Notification Action sends in-app notifications to users based on specific triggers within a workflow. 

Supported channels:

* Email - Send to user's email
* Notification - Send a notification onto the notifications icon
* SMS - Send a SMS to user's phone number

  
## Action Details

  
**Step by Step Guide**

* **Choose the Action Type:** Select "Internal Notification" from the list of available actions.
* **Name Your Action:** Enter a descriptive name for the action, such as "Internal Notification - SMS"
* **Select type of notification:** Choose between Email, Notifications and SMS as channel for the notification.  
   * **Email**:  
         * Select Email to send an email to the user's Email.  
         * Select From name and From email and Subject. If left blank, then Email will be sent using Default Values.  
         * Otherwise select a premade template along with the message to be sent.  
   * **Notification**:  
         * This will send a notification that will appear on the notification icon.  
         * Select a title and message which will appear as the notification.  
         * Select a redirect location which will be the redirection once the user clicks on the notification.  
   * **SMS**:  
         * This will send a notification to the user's phone number.  
         * Choose a template  
         * Or write a custom written sms along with attachable files.  
   * **Whatsapp:**  
         * This will send a notification to the user's phone number.  
         * Select the User Type  
         * Select the template

  
**Trigger links:** 

Trigger links can also be added in the notes using the "Trigger Links" icon.

  
**Recipients:**

You can specify individual users, user roles (e.g., all admins), or specific teams within to receive the notification.

## **Example**

**Scenario: You want to notify your sales team via Email whenever a new lead comes from FB channel.**

1. Create Workflow Trigger: Set up a workflow trigger based on new contact created with tag as FB.
2. Add contact to the opportunity pipeline
3. Assign to a user from the sales team
4. Select Internal notification with Email as channel
5. Notification Content:  
   1. Subject: "New Lead Added"  
   2. Body: "A new lead with a value of {{lead.value}} has been added. Please review the lead details immediately."
6. Save and Activate the Workflow: Once the workflow is active, your sales team will automatically receive a notification whenever the specified condition is met.

  
Attachments (1)

[ png Screenshot 2....png 118 KB ](/helpdesk/attachments/155031723354) 