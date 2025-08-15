**Date Updated:** 2025-04-09T02:32:03.000Z

The Instagram Interactive Messenger action in workflows enables automatic replies through Instagram DMs.

---

**TABLE OF CONTENTS**

* [What is Instagram Interactive Messenger?](#What-is-Instagram-Interactive-Messenger?)
* [Where To Find Instagram Interactive Messenger](#Where-To-Find-Instagram-Interactive-Messenger)
* [Components](#Components)
* [Components - Buttons & Quick Replies](#Components---Buttons-&-Quick-Replies)

---

## **What is Instagram Interactive Messenger?**

  
The workflow action Instagram Interactive Messenger allows you to automate DM conversations and also include interactive elements like buttons and quick replies. Use this in combination with Instagram comment and/or message triggers.

---

## **Where To Find Instagram Interactive Messenger**

  
Navigate to Automation > Workflows > Workflow Builder > Actions > Communication > Instagram Interactive Messenger.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042050740/original/CNVa-e83YnU4Q63pIcPVpwni9ilpRLDR6g.jpeg?1740174440)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042050767/original/SfcY1GbHKGirpkWzkr_vWI5UIeK0uPcy_Q.png?1740174546)

  
---

## **Components**

  
There are several Facebook Interactive Messenger components:

1. Action Name: the name visible in the workflow.
2. Reply Type:  
   1. Reply to Comment via DM: use this option when the trigger was a new comment and you want to create a DM conversation.  
   2. Reply to DM: use this option when you are responding to a DM.
3. Templates: these are [Snippets](https://help.gohighlevel.com/en/support/solutions/articles/155000000890) from Marketing > Snippets.
4. Message:  
   1. Body: the message builder.  
   2. Custom Values: this allows you to insert the [Custom Values](https://help.gohighlevel.com/en/support/solutions/articles/48001161575) created in Settings > Custom Values.  
   3. Trigger Links: this allows you to insert the [Trigger Links](https://help.gohighlevel.com/en/support/solutions/articles/48000981404) created in Marketing > Trigger Links.
5. Add Attachment: upload a file from your computer to attach it to the message.
6. Add file through URL: insert the URL to a file to attach it to the message.
7. Add New Button: add an interactive button to guide the conversation.
8. Add Quick Reply: add an interactive Quick Reply to guide the conversation.  
|
9. Wait Step: set the time between sending the Message-Button-File-Quick-Reply combo and moving on to the default branch.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042050793/original/wrwvfkyJLPgiTqclZ0Ybb7RDd76PcVAn7Q.png?1740174635)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042050802/original/gHfgC8y7XtWfNsujpOt9uM1v4Z-B0f40Jg.png?1740174704)

---

## **Components - Buttons & Quick Replies**

##   

The Buttons and Quick Replies are a big part of what makes this action "interactive". You can guide the conversation down pre-defined paths. Buttons and quick replies both create the same branches in a workflow. However, they serve slightly different purposes. 

  
**Buttons** are typically used for **persistent** actions and can perform tasks like redirecting to a link, opening a dialer, or triggering specific workflow branches. **They remain visible** even after the user interacts with them. You can add 3 buttons.

  
**Quick replies**, on the other hand, are designed to **guide** conversations by offering one-tap response options. They **disappear** after the user selects one, keeping the conversation focused and streamlined. You can add up to 13 quick replies.

  
In this Instagram Interactive Messenger you can either add buttons or Quick Replies in a message. Quick Replies can only be added when no attachments are included in the same message. In the Facebook Interactive Messenger action you can add Buttons, Quick Replies, and Files alongside each other in one action. 

  
Components:

1. Button: text displayed in the conversation and the label in the workflow.
2. Button: action.  
    
   1. Open Website: add a url and when the user clicks it will open the url for them in a new tab, leaving the conversation unaffected, and the buttons stays active if they scroll back to it.  
   2. Call Number: add a phone number and when the user clicks it will open their dialer for them, leaving the conversation unaffected, and the button stays active if they scroll back to it.  
   3. Perform Action: no specific event, it just creates a workflow branch and goes to the next workflow action in that branch.
3. Workflow branch created by the button.
4. Quick Reply: label in the workflow.
5. Quick Reply: text displayed in the conversation.
6. Workflow branch created by the Quick Reply.
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042050903/original/gT_I1gyhtTbw7sv1oM5Mlwc6XFil4npu7g.png?1740175004)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042050917/original/Byx0vtU8mKsr2l8R7GQiTp7nv9rubkksbQ.png?1740175114)

  