**Date Updated:** 2025-07-22T14:35:56.000Z

**Overview**\-

  
This guide explains how to move phone numbers between different sub-accounts within the HighLevel platform. It covers both **LC Phone** and **Twilio**\-connected accounts, highlights supported transfer types, outlines the steps involved, and provides troubleshooting guidance when number transfers fail due to account configurations or compliance requirements.

  
---

  
**TABLE OF CONTENTS**

   * [Step 1\. Go to SettingsNavigate to Settings > Phone Integration.](#Step-1.-Go-to-Settings%E2%80%8BNavigate-to-Settings-%3E-Phone-Integration.)
   * [Step 2\. Select ‘Move Numbers’Click on the “Move Numbers” option within Phone Integration.](#Step-2.%C2%A0Select-%E2%80%98Move-Numbers%E2%80%99Click-on-the-%E2%80%9CMove-Numbers%E2%80%9D-option-within-Phone-Integration.)
   * [Step 4\. Execute the Move Click "Move Numbers." The transferred numbers will appear in the destination sub-account.](#Step-4.-Execute-the-Move%C2%A0Click-)
   * [Supported Types of Number Transfers](#Supported-Types-of-Number-Transfers)
* [Possible reasons why we can't move the numbers:](#Possible-reasons-why-we-can't-move-the-numbers%3A)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

---

  
**Steps to Move Numbers Between Sub-Account-**

  
## **Step 1\. Go to Settings** 
Navigate to [Settings > Phone Integration](https://app.gohighlevel.com/settings/phone%5Fintegration).

  
Quick path: [](https://app.gohighlevel.com/settings/twilio)<https://app.gohighlevel.com/settings/phone%5Fintegration>
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48228662020/original/-8eUqZc4FDDRx05aH-p2Mk_4rL465VQzoQ.png?1653595122)

##   

## **Step 2\.** **Select ‘Move Numbers’** 
Click on the “Move Numbers” option within Phone Integration.

**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48298324669/original/EIPHwuE2zqRF05UAr-NH2CZrqWBOt8sY1Q.png?1684487448)**

  
**Step 3\. Choose Source & Destination**

 Select the phone number(s) to transfer and specify the destination sub-account.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48298324903/original/NoYfWq5ptNqZIQ7_PXcB1iy-ny3mBQfGUg.png?1684487517)

##   

## **Step 4\. Execute the Move** 
 Click "Move Numbers." The transferred numbers will appear in the destination sub-account.

---

## **Supported Types of Number Transfers**

* **Twilio ➝ Twilio**  
Move numbers internally between sub-accounts on a single Twilio master account.
* **Twilio ➝ LC Phone**  
Transfer numbers from a user-owned Twilio account to an LC Phone sub-account.  
[Moving numbers to an LC Phone Sub-account from the client's own Twilio account](https://help.gohighlevel.com/en/support/solutions/articles/48001240108)
* **LC Phone ➝ Twilio**  
Move numbers from an LC Phone sub-account to a personal Twilio account.  
[Moving numbers out of an LC Phone Sub-account to the client's own Twilio account](https://help.gohighlevel.com/en/support/solutions/articles/48001240107)
* **LC Phone ➝ LC Phone**  
Internal transfer between LC Phone sub-accounts using the built-in Move Numbers tool.
  
  
---

  
# **Possible reasons why we can't move the numbers:**

  
**1\. Different Twilio Master Accounts**  
If the source number is under a different Twilio master account, you'll need to manually request the transfer via Twilio Support. 

  
To perform this action, both Twilio account owners will need open a ticket with Twilio support here:

[Moving Twilio Phone Numbers to another Twilio Account](https://support.twilio.com/hc/en-us/articles/223135327-Moving-Twilio-Phone-Numbers-to-another-Twilio-project)

  
You can identify the Account SID in the Agency Settings > Twilio page > [](https://app.gohighlevel.com/settings/twilio)[](https://app.gohighlevel.com/settings/phone%5Fintegration)<https://app.gohighlevel.com/settings/phone%5Fintegration>

  
[Create a support ticket with Twilio support](https://support.twilio.com/hc/en-us/articles/360048500694-Contacting-Twilio-Support) with the following details:

Email Subject: **Moving numbers request**

  
Email Template:

  
Hi Twilio Support,

  
I would like to move the following phone number(s) to a new sub-account -

_****+1 PASTE\_TWILIO\_NUMBER\_HERE**_ 

  
Losing sub-account SID - **_E.g. AC8a0eac4ea7651eba06137bbf1a907df62d < Replace the Twilio sub-account SID where the number is currently in_** 
  
  
Gaining sub-account SID - **_E.g. AC8a0eac4ea7651eba06137bbf1a907df62d < Replace the Twilio sub-account SID here where the number should be moved to_**
  
  
Time-frame: ASAP

  
Please process this request at the earliest because it is business-critical for me

  
Thanks!
  
  
**2\. Regulatory Bundles / Address Not Configured**  
Certain numbers (e.g., Australian numbers +61) require verified bundles/addresses on the destination sub-account. Without them, the number cannot be moved.

  
To move the number, please set up a bundle/address in the destination subaccount: [Purchase Twilio Number - "Please Select Bundle/Address to Purchase Number"](https://help.gohighlevel.com/support/solutions/articles/48000981437-purchase-twilio-number-please-select-address-to-purchase-number-)

  
After the steps are done in the article above, please [create a support ticket with Twilio support](https://support.twilio.com/hc/en-us/articles/360048500694-Contacting-Twilio-Support) using the template above.

  
Error: Request failed with status code 400
  
  
**3\. LC Phone Transfer Failures**

Check out

* [Moving numbers to an LC Phone Sub-account from the client's own Twilio account](https://help.gohighlevel.com/en/support/solutions/articles/48001240108)
* [Moving numbers out of an LC Phone Sub-account to the client's own Twilio account](https://help.gohighlevel.com/en/support/solutions/articles/48001240107)
  
  
If both sub-accounts are on LC Phone and the tool isn't working, please[ contact HighLevel support ](https://help.gohighlevel.com/support/solutions/articles/48001204857-ways-to-get-highlevel-support-24-)to move the numbers for you, provide the location id of the numbers you are trying to move from and to

If the tool doesn’t work for LC Phone to LC Phone transfers:

* Moving numbers
* Provide location IDs for source and destination
* Support will escalate with Twilio if needed

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155032420067/original/hidRFwBjdZhuGqhL8_LJSmgw5E80LqqPCw.jpg?1725635357)

Note- Once you provide us with the information above, we will be able to identify the account SID and submit this in the escalation notes for the specialist to create a ticket with Twilio. 

  
---

# **Frequently Asked Questions**

Currently no frequently asked questions. Submit feedback on this article to help is add questions to this section!

---

# **Related Articles**

* [](https://help.gohighlevel.com/en/support/solutions/articles/155000002369)[Moving numbers from one Twilio account to another](https://help.gohighlevel.com/support/solutions/articles/48001177283)

  
###   

  