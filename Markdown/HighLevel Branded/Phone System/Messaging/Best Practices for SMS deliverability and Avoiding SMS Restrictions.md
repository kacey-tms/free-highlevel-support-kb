**Date Updated:** 2025-06-11T16:13:50.000Z

This article outlines essential best practices to help you improve SMS deliverability and avoid carrier restrictions. By following these guidelines, you can ensure your messages reach your audience reliably and stay compliant with carrier policies.

---

**TABLE OF CONTENTS**

* [Error and Opt-out Rate Monitoring](#Error-and-Opt-out-Rate-Monitoring)
* [What should we do when we get a violation email?](#What-should-we-do-when-we-get-a-violation-email?)
* [What are error and opt-out rates and good to have a threshold?](#What-are-error-and-opt-out-rates-and-good-to-have-a-threshold?)
* [What do I do to get the sub-account suspension removed early?](#What-do-I-do-to-get-the-sub-account-suspension-removed-early?)
* [How to prevent future SMS suspension](#How-to-prevent-future-SMS-suspension)

---

# **Error and Opt-out Rate Monitoring**

  
* We are focused on helping our customers deliver trusted communications. To make sure that the carrier does not block or suspend the account permanently based on bad usage.
* We will be monitoring the delivery rate of the overall account and be taking proactive measures(as mentioned below) to keep the delivery rate in check:  
    
   * **Violation Email -** We will send out an email notification as soon as the subaccount hits the error rate of 8% and opt-out rate of 2%.  
   * **Temporary Account Restriction -** We will send out a suspension email as the sub-account hits the error rate of 12.5% and opt-out rate of 3%.

  
**Please Note:** As soon as the account hits the temporary suspension, all upcoming outbound SMS will fail till 00:00 AM UTC.

---

# **What should we do when we get a violation email?**

  
1. Stop all your workflows, campaigns, triggers, and/or bulk actions to contacts who have not explicitly opted in to receive messages from the sub-account.
2. Enable and customise the Opt Out language and SenderID message as per your use case so that all the upcoming messages are not flagged.
3. Please discuss this with your client to ensure that no bulk communication or message blasts or cold prospecting message campaigns are sent in the near future before we receive your reply to this ticket.

---

# **What are error and opt-out rates and good to have a threshold?**

  
* A High Opt-Out Rate indicates that **contacts receiving your messages have objected, generated complaints, or marked your SMS as spam**. A good opt-out rate is typically in the range of 0—1%. Once the opt-out rate hits 2%, the sub-account will be locked for sending text messages for 24 hours.
* A High Delivery Error Rate indicates that you are **sending SMS to contacts that are no longer in service, are unreachable, or use a non-SMS-capable device such as a landline**. This may also mean that external carrier filters are refusing to deliver your SMS due to bad sending behavior in the past. A good error rate is typically in the range of 0—6%. Once the error rate hits 12%, the sub-account will be locked for sending text messages for 24 hours.

---

# **What do I do to get the sub-account suspension removed early?**

  
* The sub-account suspension will be lifted in 24 hours. However, If the sub-account is permanently suspended. Please refer to the article [Why is your account suspended](https://help.gohighlevel.com/en/support/solutions/articles/48001207676) to unsuspend the sub-account.

---

# **How to prevent future SMS suspension**

  
The sub-account should be able to send SMS after 00:01 AM UTC the next day after you received the non-compliant email. You can check the best practices below on how to reduce the error rate: 

1\. **Add Opt Out language (reply STOP to unsubscribe)** in all the first SMS sent to a new contact -  
  
[![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155000318311/original/ceM5L6iuALXxaqMtqxHwsRU94ZBqKhtQoQ.png?1685694447)](https://help.gohighlevel.com/support/solutions/articles/48001213941-isv-messaging-policy#3.-Opt-Out-Language-addition)
  
  
2\. **Add Sender information (Introduction of yourself/company)** in all the first SMS sent to a new contact- 

3\. Do not send messages to SMS-incapable devices like landlines, **Enable the Number Validation feature** for this. This feature will look up the number before sending out the message and enable and temporary DND on the contact. 

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155007734347/original/f_1um2cYazU-57T9eM3GLLpJMWf1S42Rtw.png?1694765075)  

  
4\. **Avoid sending URLs shortened using a public URL shortener** 

  
Using public URL shorteners like bit.ly or tinyurl.com can harm SMS deliverability. Carriers—especially T-Mobile and AT&T—flag these as high risk due to their association with spam and phishing.  
  
* **T-Mobile** prohibits URL cycling and multiple redirects. Messages using such tactics may be blocked.
* **AT&T** outright blocks public shorteners.

**Best Practices:** 

* Use **custom** or **branded** short URLs linked to your business domain.
* Limit redirects to **no more than one**, and avoid cloaking link destinations.
* When possible, include the **full URL** to boost transparency (even if it takes extra characters).

  
Improving your URL practices can prevent filtering and ensure your messages reach their audience.

  
5\. **Make sure the Business Profile, A2P Brand and campaign are registered:** As the messaging world is moving towards the direction where with these registrations no messages will be delivered. You can view the trust centre tab once the sub-account country is set to US: 

  
* **Info Required for Business Registration** \- <https://highlevel.canny.io/changelog/capture-ein-for-business-profile-and-a2p-brand->

  
* **Business Profile creation and registration** \- <https://highlevel.canny.io/changelog/trust-center-business-profile-creation-flow-live>

  
* **A2P Brand Registration** \- <https://highlevel.canny.io/changelog/a2p-brand-registration-better-delivery-with-reduced-filtering>

  
* **Campaign Registration and Messaging Service** \- <https://highlevel.canny.io/changelog/campaign-registration-and-messaging-service>

  
Some additional docs to help you out:   
  
* **Trust Center Support Doc** \- <https://help.gohighlevel.com/support/solutions/articles/48001225526-lc-phone-system-trust-center>

  
* **A2P Campaign Registration Best Practices** \- <https://help.gohighlevel.com/support/solutions/articles/48001229784-a2p-10dlc-campaign-approval-best-prac>

  
If the country is not set to US, you can still use the system following the best practices so that the delivery rate is high and the SMS is not flagged. A2P campaign is just a more enhanced safety net for delivery but that doesn't mean you cannot use the system without it. 

**Note** - Campaign Verification can take up to 6-7 weeks if it is not approved after the 7th week, please raise a support ticket with us to escalate the request to TCR. 

  
6.**For future website form opt-in setup, please include a checkbox to ensure the lead gives consent when filling out** the form if that's where the leads opt-in. 

You can type something like this I just grabbed it from another client as an example: 

  
By providing your name and contact information you are expressly consenting to receive communications from COMPANY\_NAME or one of their licensed agents, which may include phone calls (including to any wireless number that you provide) including automatic telephone dialling systems or by artificial/pre-recorded messages text message and/or emails for the purpose of marketing insurance products and services including health, medicare and life insurance plans. By providing your information, you understand that your consent is not a condition of the purchase of any product or services, and carrier messaging and data rates may apply. You may revoke this consent at any time by calling us at 1-800-000-000 or by emailing us at EMAIL\_HERE to be placed on our do-not-call list. 

7\. **Good to Have:** The first message should have the source of how your leads opt in. 

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155000318313/original/CdbUV4IqS1HJ_BfgCsqAOrDLVhYquft4Yw.png?1685694447)

8\. **Good to Have:** Add Opt-in language so contacts are actively double opt-in via sms and web form checkbox (reply 1 to subscribe) 

Also, sharing a [Messaging Policy](https://help.gohighlevel.com/support/solutions/articles/48001213941) which will help you further on this.