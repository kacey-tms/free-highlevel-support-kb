**Date Updated:** 2025-03-04T20:42:26.000Z
  
  
**TABLE OF CONTENTS**

* [What are Reply & Forwarding Addresses?](#What-are-Reply-&-Forwarding-Addresses?)  
   * [Where to Find Reply & Forward Settings](#Where-to-Find-Reply-&-Forward-Settings)  
   * [Forwarding Address](#Forwarding-Address)  
   * [Reply Address](#Reply-Address)  
   * [BCC Emails](#BCC-Emails)  
   * [Forward to Assigned User](#Forward-to-Assigned-User)  
   * [Enable Reply Tracking - Other SMTP Providers](#Enable-Reply-Tracking---Other-SMTP-Providers)  
         * [Example With Reply Tracking](#Example-With-Reply-Tracking)  
         * [Example Without Reply Tracking](#Example-Without-Reply-Tracking)  
   * [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What are Reply & Forwarding Addresses?**

Here are a few additional configurations that you can use to receive copies of the Emails that you get in your account using a Forwarding Address or BCC. Reply Tracking is also elaborated.

  
## **Where to Find Reply & Forward Settings**

Once you are in the location, click on **Settings -> Email Service**s

  
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031378307/original/sTiyHi3hqgNimmaOnIK2tUuzV8jltXg4GQ.jpg?1724182488)**  

---

## **Forwarding Address**

If a lead responds to an email, that response is always going to show up in **Conversations** tab, however, if you want a COPY of the lead’s email response to go to someone’ email, you could put in that email address there. [All incoming and outgoing emails (To, CC, and BCC) will be charged.](https://help.gohighlevel.com/support/solutions/articles/48001220605-what-is-lc-email-i-want-to-know-more#LC---Email-Pricing)

  
You could enter multiple forwarding email addresses here separated by a comma, e.g. [email1@test.com,](mailto:email1@test.com,) [email2@test.com](http://email2@test.com), [email3@test.com](mailto:email3@test.com,)

**IMPORTANT:** Forwarding address and BCC Emails **ONLY work when using Mailgun and LC Email.** We don't support other smtp providers.**[](mailto:kate@gohighlevel.com,)[](mailto:kate@gohighlevel.com,)[](mailto:kate@gohighlevel.com,)**

**[](mailto:ebrahim@gohighlevel.com,)[](mailto:kate@gohighlevel.com,)**

**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031378336/original/c3rgbqnGtH4wUFzgVQHWw-xOjviN0LTHvQ.jpg?1724182531)**  

---

## **Reply Address**

Now we have the option to Add a reply-to address. All incoming emails will be sent to that email address instead of routing to the Conversation tab.

  
When you reply to the leads' email in your inbox outside the CRM, your reply will not sync back to the CRM.

  
You will be able to add up to 5 email addresses.

  
This can be configured in **Settings> Email Services> Reply & Forward Settings> Reply Address.**

  
Make sure to **Save** once you have entered a Reply Address.

  
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031547525/original/19Bs496zgaiTVo1bO9nwhTXXoA-anf5jsw.png?1724400925)**  

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031378366/original/qADgEHJ_7tnNV3n3amaaOlUmjr9frQvMeQ.jpg?1724182590)

---

## **BCC Emails**

You will receive a Blind Carbon Copy of every email that goes out from that location. This is configurable from **Settings> Email Services> Reply & Forward Settings> BCC Emails**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031378457/original/e6UutfFjMKYAJTconTpaZbdXT1s829mt9Q.jpg?1724182752)

---

## **Forward to Assigned User**

The assigned user of the lead will receive the email replies in their Email Inbox. The Email will be sent to the Email address for that user in **Settings> My Staff> edit User> User Info**

[ ](https://www.loom.com/share/a590d5dd16b14278af6c6ea720950578)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031378472/original/8FqD-K9rmcAe_-g7s3oyRrYwr-6kvqjWYQ.jpg?1724182778)

---

## **Enable Reply Tracking - Other SMTP Providers**

There's no option to enable reply tracking for Mailgun since it's directly integrated with the Receiving route set up in Mailgun.[ Click here to learn more about: How to setup Replies in MailGun.](https://help.gohighlevel.com/en/support/solutions/articles/48000987293)

  
If you mask the sender email like testing@gmail.com, the reply-to address will show as **testing@replies.subdomain.com**, which is the Mailgun subdomain we set up for the location in **Agency Settings-> Mailgun.**

  
Replies will still appear correctly in the Sub-account's Conversation tab. 

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48286916898/original/w-1dICJ2Bsh_RZAP7ac2r7jnJsfEuOMb8Q.png?1678723680)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155031378496/original/gePZQCEUWIstIyH1C68WKaiSaOcgjonr8Q.jpg?1724182805)

  
### **Example With Reply Tracking**

The highlighted email shown in the screenshot below will be the reply-to email address. So we can capture the email replies back into the Conversation tab to read, manually respond or trigger a response using tags, etc. This will be the limitation of using SMTP integration. 

  
**IMPORTANT:** **We are not able to get email replies back to the Conversation tab if we copy the highlighted email below and send a direct email/ initiate a new email thread with it. We will need to reply to the email sent from the system.** 
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48260597029/original/MM1xCqK_FV3P9RIVLiwReIssTd-Qb4hbIQ.png?1667330277)
  
  
### **Example Without Reply Tracking**

The highlighted email shown in the screenshot below will be the reply-to email address. We will not be able to capture the email replies back into the Conversation tab. But responses will be going to the configured sender email in the inbox.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48260597698/original/IFF1KAgY2Qq0-jX_xY_cHqEWOSsOv33SJg.png?1667330551)

  
---

## **Frequently Asked Questions**

  
**Q:** **Why the attached files do not get forwarded along with the email replies?**

**A:** The forward settings in the email services tab do not support forwarding attachments. So if the contact replies to the emails with an attachment, we will need to log in to the HighLevel conversation view to see it.

  
**Q:** **Why do the forwarding emails I've added disappear after attempting to save?**

**A:** If the email addresses are invalid, or they collide with any dedicated domains added to your sub-account, they cannot be used as a forwarding address.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155029443187/original/_qck3ZATobcGzaVOA4RzV5XfjyYYBRnrLA.jpg?1721248883)
  
  