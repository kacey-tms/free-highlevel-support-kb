**Date Updated:** 2021-08-24T20:36:53.000Z

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48133451312/original/R5AoBeVorMls9ZwMNlyBEQNZJhZaXQaY4w.jpg?1629817330)

  
Loops occur when two Triggers either feed into each other or one Trigger feeds back into itself, creating an infinite loop of actions. Loops are detrimental to app performance because they commandeer server resources, causing a slow down for all users, which is why the system now looks for potential loops and locks the Triggers that may cause them.

  
Workflows, Triggers and Campaigns will be Loop Locked when they hit 50 Starts/Executions for the same Contact in less than 30 minutes. 

  
Example: Trigger fires 50 times for the same Contact in less than 30 minutes, or a Contact gets added to a Workflow/Campaign 50 times in less than 30 minutes.

  
If you receive a Loop error, please contact Support so that we can review the Trigger with you, fix what would cause a loop, and unlock the Trigger. 