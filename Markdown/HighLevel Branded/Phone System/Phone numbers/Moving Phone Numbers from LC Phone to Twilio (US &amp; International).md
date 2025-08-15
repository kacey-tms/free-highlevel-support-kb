**Date Updated:** 2025-07-09T16:47:52.000Z

**OVERVIEW**

  
This article provides a step-by-step guide to help agencies or clients move their phone numbers, whether US or international, from an **LC Phone Sub-account (within HighLevel) to their own Twilio account**, ensuring seamless SMS and voice functionality within the platform.

  
**IMPORTANT:** To move numbers from **LC Phone to Twilio**, customers must coordinate with both HighLevel Support and Twilio Support to obtain the required credentials and complete the transfer. Alternatively, customers can reach out directly to HighLevel Support, and we’ll guide and assist through the entire process.

---

**TABLE OF CONTENTS**

* [Before Moving Your Number](#Before-Moving-Your-Number)
* [Moving US Numbers from LC Phone to Twilio](#Moving-%C2%A0US-Numbers-from-LC-Phone-to-Twilio)  
   * [Step 1: Identify the Sub-account SID](#Step-1%3A-Identify-the-Sub-account-SID)  
   * [Step 2: Gather Twilio Credentials](#Step-2%3A-Gather-Twilio-Credentials)  
   * [Step 3: Submit a Support Ticket to Twilio](#Step-3%3A-Submit-a-Support-Ticket-to-Twilio)  
   * [Step 4: Disable LC Phone Integration (If Applicable)](#Step-4%3A-Disable-LC-Phone-Integration-%28If-Applicable%29)
* [Moving International (Non-US) Numbers from LC Phone to Twilio](#Moving-International-%28Non-US%29-Numbers-from-LC-Phone-to-Twilio)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

---

## **Before Moving Your Number**

  
Ensure you have the following information and access:  
  
* Identify whether the number is a **US number** or an **International (non-US) number.**
* **Access to the client's Twilio account (must be the account owner).**
* The Sub-account SID (Location ID) of the LC Phone Sub-account holding the number(s).
* For **US numbers**, request from HighLevel Support for the **Account SID** to reach Twilio Support for the migration process.
* For **I** **nternational numbers**, request from HighLevel Support  
   * Gaining Account SID  
   * Regulatory Bundle SID  
   * Regulatory Address SID

---

## **Moving US Numbers from LC Phone to Twilio**

  
This section outlines the step-by-step process to transfer US-based phone numbers from a LeadConnector (LC) Phone Sub-account to the client's own Twilio account. This ensures continued use of the number for SMS and voice within HighLevel while giving the client full ownership and control through their Twilio setup.

  
### **Step 1:** Identify the Sub-account SID

  
* Navigate to **Settings → Business Profile** in your HighLevel account to locate the Sub-account SID (also known as Location ID) of the LC Phone Sub-account holding the number(s).  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155045972658/original/TgMcRzrEZYfuwtTgoCcFpmuyMiBEr0NHWA.jpeg?1746109305)
* Submit a support ticket to HighLevel and request the **losing** **Sub-account SID** for this Location (Sub-account)ID.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155045972735/original/ruMK9XOl0NIlCzM2UaF8MuauyxRqZpVpiw.gif?1746109415)

### **Step 2:** Gather Twilio Credentials

  
Ensure you have the following credentials from the client's Twilio account. These can be found in the Twilio Console under the **Account Info** section.

* **Account SID**
* **Auth Token**

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155045972479/original/GXQIYZMY_e8s-NHzvx5lh8Spr7Y3lgoDyQ.png?1746109070)
  
  
### **Step 3:** Submit a Support Ticket to Twilio

  
Once you receive the losing Sub-account SID from HighLevel Support, you will need to **contact Twilio Support** to **initiate the migration process**. Follow these steps to submit the **support ticket to Twilio**:

* **Subject**: Moving numbers request
* **Phone Number(s)**: List the numbers to be moved.
* **Losing Sub-account SID**: The Sub-account SID identified in Step 1.
* **Gaining Sub-account SID**: The Sub-account SID of the client's Twilio account, identified in Step 2.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155045973045/original/siqHMu91OvfTCIbDZWzGqg6iODtA2K6s0A.gif?1746109795)

  
**Tip**: Sample Format when creating a ticket with Twilio Support  
  
**Subject:** Request to Move Phone Number(s) to New Sub-account  
  
**Priority:** P3 – General  
  
**CC:** migration@leadconnectorhq.com  
  
**Message Template:**  
  
Hi Twilio Support,

I would like to request the migration of the following phone number(s) to a new sub-account:
**Phone Number(s):** [PASTE_NUMBER(S)_HERE]
**Losing Sub-account SID:** [INSERT_LOSING_SUBACCOUNT_SID]
**Gaining Sub-account SID:** [INSERT_GAINING_SUBACCOUNT_SID]

This migration is crucial for business continuity and has been coordinated with HighLevel Support. Please initiate the transfer at your earliest convenience.
**Time-frame:** ASAP

Let me know if any further verification or information is needed.

Thanks!

###   
  
**Step 4:** Disable LC Phone Integration (If Applicable)

  
If you plan to discontinue using LC Phone for the sub-account, submit the **Disable LC Phone Form**. You'll need to provide the Sub-account ID, Twilio Account SID, and Auth Token. For more, visit: [How to Disable LC Phone System for Subaccount/Location (LC to Twilio)](https://gohighlevelassist.freshdesk.com/support/solutions/articles/48001231698-how-to-disable-lc-phone-system-for-subaccount-location-lc-to-twilio-).
  
  
**Please Note:** After submitting the request, **monitor the status of the transfer**. The tracking and progress of the number transfer will be handled on **Twilio’s end**, so it's best to follow up with Twilio Support for updates. If you initiated the request through HighLevel Support, you can also reach out to us for assistance and coordination. Once the transfer is complete, the numbers will appear in the client’s Twilio account and can be managed accordingly.

---

## **Moving International (Non-US) Numbers from LC Phone to Twilio**

  
The **process** for moving International (non-US) numbers from an LC Phone Sub-account to a client’s Twilio account is essentially the **same** as for US numbers, the only **difference** lies in the type of information(credentials) required. Instead of just the standard account credentials, international transfers require regulatory details due to country-specific compliance.

  
You’ll need to contact HighLevel Support or your Partner Manager to obtain the necessary information, including the **Gaining Account SID, Regulatory Bundle SID, and Regulatory Address SID**. Once you have these details, submit a support ticket to Twilio, listing the international number(s) and all required SIDs. Clearly state that it’s an international number transfer from LC Phone to Twilio. Twilio will handle the request under local regulations and complete the transfer upon approval.

---

## **Frequently Asked Questions**

  
**Q: How long does the number transfer process take?**  
The transfer typically takes 1–3 business days after submitting the request to Twilio Support. This is the usual timeframe; however, processing times can vary. We recommend reaching out to Twilio Support directly for the most accurate and up-to-date status on your specific request. 
  
  
**Q: Will there be any downtime during the transfer?**  
There might be minimal downtime. It's recommended to schedule the transfer during off-peak hours.
  
  
**Q: Can I transfer multiple numbers at once?**  
Yes, you can list multiple numbers in the support ticket to Twilio.

---

## **Related Articles**

* [Moving US numbers from Twilio to LeadConnector(LC)](https://gohighlevelassist.freshdesk.com/support/solutions/articles/48001240108-moving-us-numbers-from-twilio-to-leadconnector-lc-)
* [Moving Numbers tool across sub-accounts](https://help.gohighlevel.com/support/solutions/articles/48001203968-moving-numbers-tool-across-sub-accounts)