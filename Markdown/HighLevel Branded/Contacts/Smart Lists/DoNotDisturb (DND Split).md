**Date Updated:** 2022-11-17T01:08:13.000Z

**DND can now be set to individual channels (FB, SMS, Calls, Emails, GMB, WhatsApp) once they are integrated with the system.**   
  
[What's changed?](#What's-changed?)

#### [What integrations channels will this affect?](#What-integrations-channels-will-this-affect?)

####   
**Emails** 
[How does it work in the case of emails?](#How-does-it-work-in-the-case-of-emails?)

#### [How to remove email DND for a Contact?](#How-to-remove-email-DND-for-a-Contact?)

####   
**SMS** 
[How does it work in the case of SMS?](#How-does-it-work-in-the-case-of-SMS?)

#### [How to remove SMS DND for a Contact?](#How-to-remove-SMS-DND-for-a-Contact?)

#### [Temporary -> Can be updated from within the contact record](#Temporary--%3E-Can-be-updated-from-within-the-contact-record)
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48224624468/original/JDb2HH3OFgLIB2wVWrJ7pegcjQ1te6Ps1w.png?1652131145)

  
## **What's changed?**

* Contacts that had **DND switched ON** previously - The system will continue to respect their wishes
* Contacts that did **N** **ot** have DND switched on previously, the system will continue as before

  
**DND Statuses**

* **DND ‘On’** \- now means NO automated/ manual outbound messages are permitted to go out (previously, we let people send outbound messages manually and only restricted ‘Automated’ messages)
* **DND ‘Off’** \- all automated/manual messages continue to work as usual
* **DND ‘Partial’** \- Some Channels are unavailable for Outbound messaging (THIS IS NEW!)
  
  
---

## **What integrations channels will this affect?**

  
If the integrations _(FB, SMS, Calls, Emails, GMB, WhatsApp)_ exist and are functional, they’ll get enlisted as channels that HL Users can either enable or disable independently or all together at once.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48224625381/original/RirNynW76_p5Qt0PMC0mIABKKUkbQUETWA.png?1652131555)

  
**If the Integrations drop or are disconnected** **please continue to** **re-connect.** Once reconnected the previous state in which the contact DND was set to, would be respected - meaning if you DND’d a contact for FB Messenger, it’ll continue to DND that contact in FB Messenger.
  
  
---

## **How does it work in the case of emails?**

  
The system will **Auto-Enable** **DND** for contact if the criteria below is met:

  
* **ISP email permanent failures such as** bounce, generic, suppress-complaint, suppress-unsubscribe, and suppress-bounce. ([Understanding Mailgun Suppressions](https://help.mailgun.com/hc/en-us/articles/360012287493-Understanding-Mailgun-Suppressions-Bounced-Complained-Unsubscribed-And-Whitelisted-))
* **When a recipient unsubscribes** or marks the email as **SPAM** (Mailgun complaint event).

  
**Please Note:**

Location/agency users will then have the option to **disable** the DND from within the contacts record for all the above reasons, **except** when marked as **SPAM.**
  
  
## **How to remove email DND for a Contact?**

When a user is marked as DND for any **bounce and or suppressions events,** please head into Mailgun or your ISP provider andremove the contacts email from the suppression list, then continue to validate the email before enabling the DND in the system.
  
  
---

## **How does it work in the case of SMS?**

  
**There are 2 ways in which the DND will be enabled:**

1. If the customer replied with **Opt-Out keywords** like **STOP, UNSTOP, UNSUBSCRIBE, or CANCEL**
2. If we get [30003](https://support.twilio.com/hc/en-us/articles/360008508774-Error-30003-Message-Delivery-Unreachable-destination-handset-when-Sending-SMS), [30004](https://support.twilio.com/hc/en-us/articles/360008705094-Error-30004-Message-Delivery-Message-blocked-when-Sending-SMS), [30005](https://www.twilio.com/docs/api/errors/30005), [30006](https://www.twilio.com/docs/api/errors/30006) any of these error codes from Twilio

  
| **Response Code** | **Code Description**                | **Remediation**      |
| ----------------- | ----------------------------------- | -------------------- |
| 30005             | User Inactive/Number does not exist | Enable Temporary DND |
| 30003             | Out of Service/Carrier Filtering    | Enable Temporary DND |
| 30004             | Do not want SMS/DND enabled         | Enable Permanent DND |
| 30006             | Landline/Incapable to receive SMS   | Enable Temporary DND |

  
**Two types of DND will be applied to a contact**

1. **Temporary ->** If we get **30003,** **30005** and **30006**
2. **Permanent ->** If we get **30004** or receive **Opt-Out** keywords mentioned above
  
  
## **How to remove SMS DND for a Contact?**

* **Temporary ->** Can be updated from within the contact record
* **Permanent ->** Cannot be updated from within the contact record, it can only be removed if the contact replies with **START** or the agency shares the contact's **Opt-in info** with support. Once approved, support will remove the contacts DND.

  
**Please Note:**

When sharing your opt-in info please include the relationship number(s), contact, and a loom showing the contacts opt-in permission

  
---

#   