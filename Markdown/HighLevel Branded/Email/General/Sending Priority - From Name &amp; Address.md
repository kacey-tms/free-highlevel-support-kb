**Date Updated:** 2025-04-21T21:55:19.000Z

Note: Now that Workflows are live in all accounts, you can do everything that Triggers and Campaigns do (and more!), all in one builder! [Click to learn more about Workflows](https://help.gohighlevel.com/support/solutions/articles/48001179678-workflow-builder-overview).

## 

**Covered in this article:**

  
[**Which sender email should the leads be getting the emails from?**](#Which-configured-sender-email-will-the-leads-be-getting-the-emails-from?)

**[How to check if the contacts are assigned or unassigned](#How-to-check-if-the-contacts-are-assigned-or-unassigned)**

[**Places you can configure the sender email - Manual email**](#Places-you-can-configure-the-sender-email---Manual-email)

* [Conversation tab](#Conversation-tab)

[**Places you can configure the sender email - Automated emai**l](#Places-you-can-configure-the-sender-email---Automated-email)

* [Email template](#Email-template)
* [Bulk action - Send Email](#Bulk-action---Send-Email)
* [Workflow Send Email Action](#Workflow-Send-Email-Action)
* [Campaign configuration](#Campaign-configuration)
* [Triggers - Send email action](#Triggers---Send-email-action)
  
  
## **Which sender email should the leads be getting the emails from?**

  
| | Cases                                                         | Unassigned Contact                                                                                                                                                                 | Assigned Contact |              |
| --------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- | ------------ |
| Manual Emails                                                   | Logged in user email                                                                                                                                                               | 1st priority     | 1st priority |
| | Location Email                                                | N/A                                                                                                                                                                                | N/A              |              |
| | Assigned User Email                                           | N/A                                                                                                                                                                                | N/A              |              |
| | Agency Email                                                  | N/A                                                                                                                                                                                | N/A              |              |
| Automated Emails                                                | Campaign/workflow settings                                                                                                                                                         | 1st priority     | 1st priority |
| | Assigned User Email                                           | N/A                                                                                                                                                                                | 2nd priority     |              |
| | Location Email                                                | 2nd priority                                                                                                                                                                       | 3rd priority     |              |
| | Agency Email                                                  | 3rd priority                                                                                                                                                                       | 4th priority     |              |
| Review Request Emails                                           | We will always use the **Logged in user email** as the sender email                                                                                                                |                  |              |
| Appointment request emails(calendar settings->3\. Confirmation) | We will use [do-not-reply@replies.domain.com](mailto:do-not-reply@replies.domain.com) depending on the Mailgun subdomain you set up for the location, or the SMTP integrated email |                  |              |

  
_Not sure how to connect your SMTP pro_vider? [Follow these steps to set it up.](https://help.gohighlevel.com/en/support/solutions/articles/48001059689)
  
  
If you are using Mailgun/LC Email, we will use the Business email here if the lead is not assigned:

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48284065068/original/_D4r87GpETbQ4wu9GBdG_l_CWVzA8d0xAg.png?1677519077)

---

## **How to check if the contacts are assigned or unassigned**

Search for the contact in the Smart Lists tab

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188206753/original/UFrUKvNK3nZu06hd1I3oQrKJckRJA4APTw.png?1644355700)
  
  
Search Conversations -> Click on the icon on the right to view the Contact Details

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188204345/original/-GrI_8A3X5jdM83EmqcC1aH3THqOJeEvzQ.png?1644355100)
  
  
Check who is assigned to the contact here:![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188204428/original/eWuvFMaPx6uRVZwCax4FYtOmvikmcXW6Vg.png?1644355122)

---

## **Places you can configure the sender's email - Manual email**

## **Conversation tab**

The From email will be the user logged in email by default:![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188192554/original/5Ehmg0KbCZ-cmpy37kyBIoLPJkCM5Tqp9w.png?1644351562)

  
However, if you have 2-way email sync set up, the email will show the integrated email:[](https://help.gohighlevel.com/en/support/solutions/articles/48001235216)

[How to Set Up Two Way Email Sync for Gmail](https://help.gohighlevel.com/en/support/solutions/articles/48001235216)[](https://help.gohighlevel.com/en/support/solutions/articles/48001229663)

[Two Way Email Sync for Outlook](https://help.gohighlevel.com/en/support/solutions/articles/48001229663)

---

## **Places you can configure the sender's email - Automated email**

## **Email template**

Click on **Marketing** \> **Emails** \> **Templates** \> **+New**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48284066845/original/vrc_pIS7VysZM0ddYPIpoi1T6ThRiOGSmA.png?1677519700)

  
![](https://i.ibb.co/F0PmndC/2023-1-27-9-39-42.gif)

---

### **Bulk action - Send Email**

Click Contacts ->Smart Lists -> Select Contacts -> Click Send Email![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188200986/original/dqBZMq08GHX2kFqqf0fkxLQawEcVfewH0Q.png?1644354218)

  
Add the **From Name** and **From Email**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188201325/original/nK4iJ2tcPcGlorB-HEPxonM4XpGPhkGVLg.png?1644354291)

---

### **Workflow settings**

Click Automation -> Workflows -> Create Workflow![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188196331/original/DKoMjfldpZ0Pc3rLmpzPU_OhaPa9bx_gDA.png?1644352673)

  
Select **Start from scratch** and click **Create new workflow**:![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188196478/original/naT0RPIGr2aAV2-wSWy28NPt_ILjuBu4oA.png?1644352728)

  
Click Settings -> Configure Sender Address![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188196538/original/v448r_kaIzAtApn5Q3JIwQzEHENr6WGUbg.png?1644352751)

---

## **Workflow Send Email Action**

Click on the **\+ button** \> Select the "**Send Email**" option![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188197568/original/3-z1ZoODk37CNPJCwhf7UJMTCbW_jjhMAQ.png?1644353152)

  
Enter the **From Name** and **From Email**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48188197655/original/oyJjrDwT82gt4KGgagSY4jYPeVCYSmIWng.png?1644353181)

---

## **FAQs**

### **1\. Why is the From email for outlook always look long and strange?**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48257301042/original/spc9PucOJ-wT0rT3Sf4IBvjR6JcaJn-1QQ.png?1666018222)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48257301207/original/D6asla-m-OdXThoGwKQTtT1P_GnYyRIpsg.png?1666018251)

  
This is an issue with how Outlook displays the sender's information. If you send this email to gmail.com, it will show the sender's information correctly in Gsuite. 

Learn more about how to [Hide "sent by" information in Outlook](https://stackoverflow.com/questions/35148098/hide-sent-by-information-in-outlook/35149628)

### **2\. How to remove send via information in Gmail?**

  
Make sure to use the same sender email domain that matches the Mailgun domain you set up. Learn more about [the Extra info next to sender’s name](https://support.google.com/mail/answer/1311182)

---

  
## **Related Articles**

  
* [Setting Up SMTP Providers](https://help.gohighlevel.com/en/support/solutions/articles/48001059689)
* [ Email Sending Guide: Email Best Practices & Email Warm Up](https://help.gohighlevel.com/en/support/solutions/articles/155000001021)
* [How to Set Up Two Way Email Sync for Gmail](https://help.gohighlevel.com/en/support/solutions/articles/48001235216)
* [How to Set Up Two Way Email Sync for Outlook](https://help.gohighlevel.com/en/support/solutions/articles/48001229663)
* [Using Custom Email Domains with Mailgun](https://help.gohighlevel.com/en/support/solutions/articles/155000002561)
* [Limitation of using SMTP when emails are not sending](https://help.gohighlevel.com/en/support/solutions/articles/48001203144)
  
  