**Date Updated:** 2024-10-15T16:15:17.000Z

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Action Name](#Action-Name)
* [Action Description](#Action-Description)
* [Action Details](#Action-Details)
* [Example](#Example)

##   

## Overview

The **Assign User** action allows you to allocate specific contacts to designated users. This action is essential for managing workflows and ensuring that contacts are assigned to the right team members, either directly or using a round-robin assignment. This feature helps streamline tasks and maintain an organized approach to customer relationship management.

  
## Action Name

**Assign User**

  
## Action Description

This action assigns a contact to a specific user or multiple users within the system. You can assign contacts to users based on your organisational needs or use the round-robin method to distribute contacts evenly among multiple users. There's also an option to apply this action only to unassigned contacts, ensuring that reassignment doesn't occur unnecessarily.

  
## Action Details

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155032055778/original/xTYatckBkze-E3_JAgViaNy5iWKLwJv75w.png?1725268527)

  
| Field Name                        | Description                                                                                                               | Mandatory |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | --------- |
| Action Name                       | Enter a name for this action. This helps you identify the purpose of the action in your workflow.                         | Yes       |
| Users                             | Select one or more users to whom the contact should be assigned. For round-robin, select multiple users.                  | Yes       |
| Only Apply to Unassigned Contacts | Toggle this option to ensure that only unassigned contacts are assigned. If switched off, all contacts can be reassigned. | No        |

  
**How to Configure the Assign User Action**:

1. **Action Name**: Provide a descriptive name for the action, such as "Assign to Sales Rep" or "Round Robin Assignment."
2. **Users**: Click on the dropdown and select one or more users from the list. If you want to use round-robin assignment, choose multiple users.
3. **Only Apply to Unassigned Contacts**: Toggle this option on to restrict the action to only unassigned contacts. This helps in preventing overwriting existing user assignments.

**Note :** A dropdown option in users option section allows users to select between a standard value or a custom value picker.

* Standard Values: Users can input data based on the field type (e.g., date, dropdown, tag).
* Custom Value Picker: Users can input data from custom fields, such as values from an inbound webhook trigger or other custom fields.

  
**Some Triggers to Combine with This Action (But not limited to)**

1. **New Lead Created**: When a new lead is created, use this trigger to automatically assign the lead to a sales representative.
2. **Contact Changed**: Use this trigger to reassign a contact if certain conditions change, such as a contact's tag or status update indicating they need more personalized attention.
3. **Form Submitted**: Trigger this action when a specific form is submitted, ensuring that the contact is immediately assigned to a user for follow-up.

  
## Example

**Configuration Example**:

You have a workflow where new contacts from your website's lead form need to be distributed among your sales team for follow-up.

* **Action Name**: "Assign New Lead"
* **Users**: Select all the sales team members (e.g., "John Doe," "Jane Smith," "Alex Johnson").
* **Only Apply to Unassigned Contacts**: Toggle this option on to ensure only new, unassigned contacts are distributed.

  
**Workflow Steps**:

1. **Trigger**: Form Submitted - This trigger activates when a new lead submits a form on your website.
2. **Action**: Assign User - Configured to distribute the new lead to one of the selected sales team members using round-robin.
3. **Action**: Send Notification - Optionally, send a notification email or SMS to the assigned sales rep to inform them of the new lead.