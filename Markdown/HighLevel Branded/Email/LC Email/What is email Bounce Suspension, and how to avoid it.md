**Date Updated:** 2024-07-25T02:51:22.000Z

Email sending will be suspended for having a high hard bounce rate. Email providers and anti-spam networks monitor bounce rates for every email you send and use that information to suspend email sending for your accounts with high bounce rates. High bounce rates will impact your email deliverability.

  
In this article, you will learn about

1. Bounce
2. Causes an account suspension
3. Fix the hard bounce and activate the account

---

#### **Covered in this Article:**

* #### [What are bounces?](#What-are-bounces?)
* #### [What causes an account suspension](#What-causes-an-account-suspension)  
      * #### [How long will email sending be blocked?](#How-long-will-email-sending-be-blocked?)
* #### [What should you do now?](#What-should-you-do-now?)
* #### [How to prevent future account suspension:](#How-to-prevent-future-account-suspension%3A)  
   * #### [Email Best Practices: ](#Email-Best-Practices%3A-%C2%A0)  
         * #### [1\. Email Validation](#1.-Email-Validation)  
         * #### [2\. Set up your dedicated domain](#2.-Set-up-your-dedicated-domain)  
         * #### [3\. Configure the sender email that matches the dedicated domain you set up](#3.%C2%A0Configure-the-sender-email-that-matches-the-dedicated-domain-you-set-up)  
         * #### [4\. Schedule the emails in little batches](#4.-Schedule-the-emails-in-little-batches)  
         * #### [5\. Set up double opt-in](#5.-Set-up-double-opt-in)  
         * #### [6\. Set up Unsubscribe Links](#6.-Set-up-Unsubscribe-Links)

  
---

# **What are bounces?**

A bounce occurs when an email is not delivered or rejected by the recipient's email provider.

  
There are two types of bounces.

1. **A hard** bounce occurs when an email address does not exist.
2. **A soft** bounce is a temporary failure, and some more reasons, like the recipient servers being down or the mailbox being full.
  
  
---

# **What causes an account suspension**

We have thresholds in place to monitor bounce rates, and if a Bounce rate exceeds the industry threshold (below 5%), we temporarily suspend the email sending for the account. 

  
A high bounce rate indicates that the account is sending emails to contacts that are invalid emails. This may also mean that external spam filters are refusing to deliver emails due to bad sending behavior in the past. A good bounce rate is typically in the range of 0 - 3%.

  
During the email-sending suspension, only email-sending will be disabled. All other features will be working.

  
### **How long will email sending be blocked?**

A temporary block of 12 hours will be enforced. Users can quickly resume sending by enabling email validation. If this happens for the third time in seven days, email sending will be blocked permanently until the email validation feature is enabled.

---

# **What should you do now?**

When a sub-account/ location is suspended, you will receive an email to the sub-account/ location accounts email address to do the below step:

  
1. Cleanse your contacts with [Email Validation Service](https://help.gohighlevel.com/support/solutions/articles/48001235221-how-to-enable-and-rebill-lc-email-validation) to eliminate addresses that are invalid/non-existent and ultimately bounce.
2. If the sub-account is a client, please discuss this with your client and advise them not to send bulk communication or cold email campaigns until this issue is resolved.

  
Not following the recommended remediation measures may result in restrictions on email capabilities for this location. Please note if your Complaint, Unsubscribe, and/or Hard Bounce rates continue to deteriorate this sub-account may get blocked.

  
---

# **How to prevent future account suspension:**

The location should be able to send emails 24 hours after you receive the non-compliant email notification. 

Right now, we don't have any way to easily locate the remaining people that didn’t get the email before it was blocked. 

The only workaround would be to export the email statistics and then reupload to tag the leads, then use smart list to filter to the leads without that tag to re-send again: 

Learn more about [Email Statistics](https://help.gohighlevel.com/en/support/solutions/articles/48001215386)
  
  
If you don't want to receive these emails, please change the user role to a **user** instead of an **agency admin**. 

[![](https://i.ibb.co/TckmLt0/2023-2-2-11-38-11.gif)](https://i.ibb.co/TckmLt0/2023-2-2-11-38-11.gif)
  
  
---

## **Email B** **est Practices:** 

### **1\. [Email Validation](https://help.gohighlevel.com/en/support/solutions/articles/48001235221)**

Since we are not showing any reporting on which contacts are bounced. If those contacts were uploaded from previous options, we highly recommend **validating all existing contacts** before sending them. 

  
Once you are in the agency view > Sub-accounts > Click on the sub-account name > Scroll down to **Enable Re-validation for 90 days.** 

The bounce emails will be marked as invalid emails, so you don't need to tag them as invalid emails will not be picked in the campaign/bulk/workflow.

[![](https://i.ibb.co/yqmqcQH/2023-2-2-9-36-15.gif)](https://i.ibb.co/yqmqcQH/2023-2-2-9-36-15.gif)

  
**2\. Set up your dedicated domain**

[How to Set Up a Dedicated Sending Domain (LC Email)](https://help.gohighlevel.com/en/support/solutions/articles/48001226115)

###   
**3\.** **Configure the sender email that matches the dedicated domain you set up**

[Masking Sender Emails - From Name & Address](https://help.gohighlevel.com/en/support/solutions/articles/48000979925)

[Email Authentication - DMARC](https://help.gohighlevel.com/en/support/solutions/articles/48001224630)

  
So if you set up replies.yourcompany.com, you can send from sender\_name@company.com 

###   
**4\. Schedule the emails in little batches**

[Bulk Actions For Contacts & SmartLists](https://help.gohighlevel.com/en/support/solutions/articles/48001167703)

###   
**5\. Set up** **double opt-in**

To set up double opt-in for future setup, please include a checkbox to ensure the lead gives consent when filling out the form if that's where the leads opt-in: 

You can set up a checkbox like this:

By providing your name and contact information, you are expressly consenting to receive communications from COMPANY\_NAME or one of their licensed agents, which may include phone calls (including to any wireless number that you provide), including automatic telephone dialing systems or by artificial/pre-recorded messages text message and/or emails for marketing insurance products and services including health, medicare, and life insurance plans. By providing your information, you understand that your consent is not a condition of the purchase of any product or services, and carrier messaging and data rates may apply. You may revoke this consent at any time by calling us at 1-800-000-000 or emailing us at EMAIL\_HERE to be placed on our do-not-call list. 

###   
**6\. Set up** **Unsubscribe Links**

[ How to Set Up Unsubscribe Links for LC - Email](https://help.gohighlevel.com/en/support/solutions/articles/48001225534)

---
  
  