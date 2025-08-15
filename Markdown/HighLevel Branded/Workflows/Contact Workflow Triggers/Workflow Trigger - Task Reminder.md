**Date Updated:** 2024-09-01T16:45:32.000Z

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Trigger Name](#Trigger-Name)
* [Trigger Description](#Trigger-Description)
* [How to Configure](#How-to-Configure)
* [Example](#Example)

##   

## Overview

The **Task Reminder** trigger allows you to set up workflows that are activated based on reminders for tasks. This can be helpful for sending notifications to users to remind them of upcoming tasks or to take action if a task is overdue.

  
## Trigger Name

**Task Reminder**

  
## Trigger Description

This trigger is activated based on reminders associated with tasks. You can use filters to determine when the reminder should activate the workflow, such as a specific number of days before or after the task's due date.

  
## How to Configure

* **Choose a Workflow Trigger**: Select **Task Reminder** from the list of available triggers.
* **Workflow Trigger Name**: Enter a descriptive name for your trigger, such as "Task Reminder."
* **Filters**: Use filters to define when the reminder should trigger the workflow. These filters allow you to specify time-based conditions relative to the task's due date.

  
| Value              | Description                                                                      | Mandatory |
| ------------------ | -------------------------------------------------------------------------------- | --------- |
| After no. of days  | Specifies the number of days after the task's due date to trigger the workflow.  | No        |
| Before no. of days | Specifies the number of days before the task's due date to trigger the workflow. | No        |
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155032022436/original/UhjMT1LpVt_4D7vAQPMzvTlF1uFYd1uSiw.png?1725189246)

##   

## Example

  
You want to create a workflow that sends an email reminder to a user three days before a task is due. The workflow will also update the task status to "Reminder Sent."

* **Workflow Trigger Name**: "Pre-Due Task Reminder"
* **Filters**:  
   * **Before no. of days**: "3" (Trigger the workflow three days before the task's due date)

  
**Workflow Steps**:

1. **Trigger**: Task Reminder (as configured above)
2. **Action**: Send Email - Notify the assigned user about the upcoming task due date.
3. **Action**: Update Task Status - Change the task status to "Reminder Sent."