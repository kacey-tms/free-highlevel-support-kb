**Date Updated:** 2023-02-20T23:55:29.000Z

Primary rule: 

  
If the User (who logged in to send the SMS) is in the sub-account's My staff tab and has a Twilio Number assigned to himself or herself, the lead will get the SMS from the **Twilio number** **assigned** to that User. If the Twilio number is **SMS incapable**, we use **the default number** to send out the SMS instead.

  
Learn more about [Phone numbers for users / Assign Twilio Numbers to Users](https://help.gohighlevel.com/en/support/solutions/articles/48001152124)

  
Go to sub-account **Settings** \> **My staff** \> Edit the user

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48282699342/original/pgEfe1-dT3q_puEcFshp8meGOwEjKOlIJg.png?1676916351)

  
Expand **Call & Voicemail Settings**

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48282699293/original/KHDtJLTrnrOYBmrCSrqXoBk4cigFAbmoqw.png?1676916321)

## If the User (who logged in to HL) is not inside that sub-account OR the User doesn't have a Twilio number assigned, we will first use

  
### **1\. Channel number (first Twilio number ever used with that contact)**

  
If that number got removed, we will then use:

  
### **2\. Default outbound number**

  
![](https://i.ibb.co/YjHc479/chrome-capture-2023-1-20.gif)

  
When we hover over the text messages in the conversation, we can click on the three dots to view **D** **etails**. This helps to indicate which Twilio number is used when sending SMS.

  
Check out why [SMS still coming from old Twilio number when I got a new one?](https://help.gohighlevel.com/en/support/solutions/articles/48001152123)