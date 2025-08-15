**Date Updated:** 2024-08-28T23:09:44.000Z

**Troubleshooting SMS Forwarding Issues in HighLevel**

If you're experiencing issues where incoming SMS messages are only visible in the conversation tab and not being forwarded to your designated forwarding number, this article is here to help. We'll guide you through the common reasons behind this problem and provide step-by-step solutions to ensure your SMS forwarding functions correctly. By following the troubleshooting steps outlined, you can resolve the issue and ensure that all incoming messages are properly redirected to your forwarding number.
  
  
**TABLE OF CONTENTS**

   * [Step 1: Click on Automation > Workflows > Create workflow](#Step-1%3A-Click-on-Automation-%3E-Workflows-%3E-Create-workflow)
   * [Step 2: Choose Start from scratch](#Step-2%3A-Choose-Start-from-scratch)
   * [Step 3: Click on Add New Workflow Trigger](#Step-3%3A-Click-on-Add-New-Workflow-Trigger)
   * [Step 4: Click on Customer Replied](#Step-4%3A-Click-on-Customer-Replied)
   * [Step 5: Click on Add filters](#Step-5%3A-Click-on-Add-filters)
   * [Step 6: Select Reply channel](#Step-6%3A-Select-Reply-channel)
   * [Step 7: In the reply channel dropdown, choose SMS](#Step-7%3A-In-the-reply-channel-dropdown,-choose-SMS)
   * [Step 8: Click on Save Trigger](#Step-8%3A-Click-on-Save-Trigger)
   * [Step 9: Click on Send Internal Notification](#Step-9%3A-Click-on-Send-Internal-Notification)
   * [Step 10: Click on Custom Values > Message > Message Body](#Step-10%3A-Click-on-Custom-Values-%3E-Message-%3E-Message-Body)
   * [Step 11: Click on Contact > First Name](#Step-11%3A-Click-on-Contact-%3E-First-Name)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

  
---

  
We will only receive the inbound messages in the Conversation tab using Highlevel's mobile app and web app.

Incoming SMS will not be forwarded to the forwarding number

You set up a **Customer replied** workflow trigger like this with the Custom Value **{{message.body}}**
  
  
## **Step 1: Click on Automation > Workflows > Create workflow**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839426/original/B6QbV9UuMwGP0UxtJ3nKADzM0-gKIdTNOQ.jpg?1724866267)
  
  
## **Step 2: Choose Start from scratch**

  
Click on **Create new workflow**

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839436/original/Vl2SPNrTaeS23HL5Kggn1OlDp51tPDYg9g.jpg?1724866298)
  
  
## **Step 3: Click on Add New Workflow Trigger**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839457/original/nAhfhR63Xmkp5LtByt8nkJNueEDGxeGuKQ.jpg?1724866337)
  
  
## **Step 4: Click on Customer Replied**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839483/original/Fzf3L_pVTACs5gDnvADMoe7HBftPy38rvQ.jpg?1724866372)
  
  
## **Step 5: Click on Add filters**
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839514/original/XHT3xyAEj-_PyFPeWS7GQBD6LqQ9MvEjOQ.jpg?1724866403)
  
  
## **Step 6: Select Reply channel**

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839551/original/bq9nRH-BjzCK3CJ-ovJTkiDmmk_v2gcEIg.jpg?1724866432)

  
## **Step 7: In the reply channel dropdown, choose SMS**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839569/original/GgdC-8jIEPXdTeucOehbp4yI1n2Hun18Dg.jpg?1724866456)
  
  
## **Step 8: Click on Save Trigger**

  
Click on **Add your first Action**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839594/original/Yfvxg6fr_FEesUqxPMQUN_rVKZkpF7hXDQ.jpg?1724866491)

  
## **Step 9: Click on Send Internal Notification**
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839674/original/-U6WaCdaCC4Xyw6ceWCQG9pjw4TxuhnfBA.jpg?1724866520)
  
  
Note: SMS notification will create charges for every sms sent

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839715/original/tpXQ1iyeRFvGui7Qgx76N452LlhJP5yPrw.jpg?1724866557)

  
## **Step 10: Click on Custom Values > Message > Message Body**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839742/original/cuCEght9k0ZAvPXvaUWcMvauZ3GB3iI0WA.jpg?1724866585)
  
  
## **Step 11: Click on Contact > First Name**
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031839759/original/Hc1n_IZBRIPV4qgnuxHhO-QN4PxAhm7New.jpg?1724866616)

---

# **Frequently Asked Questions**

Currently no frequently asked questions. Submit feedback on this article to help is add questions to this section!

---

# **Related Articles**

* [Workflow - Send SMS Actions](https://help.gohighlevel.com/a/solutions/articles/155000002474?portalId=48000045315)[](https://help.gohighlevel.com/en/support/solutions/articles/155000002369)

  