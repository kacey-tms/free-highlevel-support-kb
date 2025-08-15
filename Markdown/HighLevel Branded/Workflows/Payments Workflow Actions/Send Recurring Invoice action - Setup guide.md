**Date Updated:** 2025-07-24T16:37:32.000Z

Automate your billing by embedding a Send Recurring Invoice action into any workflow.  
Below is a step-by-step guide —to configure every detail, including Action Date behavior, start/stop rules, frequency, and auto-payment.

##   

## Prerequisites

* You’ve created at least one Invoice Template in your Invoices area.
* A payment gateway (Stripe, PayPal, etc.) is configured.

##   

## How to use?

## 1\. Add the “Send Recurring Invoice” Action

1. In the Workflow Builder, click the “+” connector where you’d like invoices to begin.
2. In the Actions sidebar, search for invoice.
3. Select Send Recurring Invoice.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398092/original/B5OJ-XQo28oPGlSzqkjeIjIcN3IaaZtyIA.png?1750162732)

##   

## 2\. Configure Basic Settings

| Field            | Description                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------ |
| Action Name      | Rename from “Send Recurring Invoice” to something descriptive (e.g. “Monthly Membership”). |
| From User        | Choose which user/profile the invoice is sent “from.”                                      |
| Invoice Template | Pick your pre-built template.                                                              |
| Payment Mode     | Toggle Live (real charges) or Test (sandbox mode).                                         |
| Channel          | Select the Channel (Email, SMS, or Email & SMS) for delivery of the Invoice                |

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398090/original/PzWKoNnro5Erbw67F_3zVWwMZKpIGtFK-A.png?1750162731)  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050367029/original/1JNRaYEEEDfschid7uCtCF2chiXqm7v5oA.png?1753355239)  

## 3\. Start Date Options

### A. Action Date

* Definition: Uses the date when the contact enters this step (e.g. Contact Created, Form Submitted, Birthday Reminder). This sets the Recurring schedule's start date. The first Invoice can be sent immediately if Action Date is selected in all further settings.
* Behavior:  
   * First invoice fires immediately (at enrollment) or on the next business cycle depending on your frequency.  
   * Subsequent invoices follow the same calendar offset.  
   * Note: Once start date is selected as Action Date -> Make sure to select Action Date in all further frequency settings like date, day of the week etc.
* Use When: You want each contact’s billing cadence tied to their trigger event (e.g. user signs up on June 5 → bills on the 5th of each subsequent month).

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398341/original/kwXclAMTFBhBSbEovC7U1ZmMryQOl2crIw.png?1750162864)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398091/original/rCXzMO0L4BF5Vnp0BhQpuzRpd2cliagMig.png?1750162732)

### B. Fixed Date

* Definition: Uses a specific calendar date you select (e.g. July 1, 2025).
* Behavior:  
   * The Invoice schedule's start date is the chosen date, regardless of when the contact enters the workflow.  
   * Contacts enrolled after the fixed date will receive their first invoice on the next scheduled run.
* Use When: You need everyone billed on a universal date (e.g. 1st of each month) and don’t care about individual signup dates.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398094/original/OzGZMmkZmkVPC3L7KKoMD0fqFsyNyKMj7Q.png?1750162732)

##   

## 4\. End Criteria

| Option              | Configuration                                         | Example                         |
| ------------------- | ----------------------------------------------------- | ------------------------------- |
| Never               | Runs indefinitely until manually stopped.             | Ongoing subscriptions.          |
| After X Occurrences | Enter the total number of invoices to send (e.g. 12). | A 12-month course billing plan. |

## ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398093/original/yG_AXzM1WMxryG5eRM-aDehyOhWrIPyioQ.png?1750162732)

## 5\. Recurrence Frequency

1. Under How Often?, choose one of:  
   * Daily  
   * Weekly  
   * Monthly  
   * Yearly
2. Configure each frequency as follows:

### Daily

* Every X Day(s): e.g. every 4 days → enter “4.”

### Weekly

* Select Day of Week:  
   * Action Date → the weekday of the trigger (e.g. if enrolled on a Tuesday → bills every Tuesday).  
   * Specific Day → pick Monday, Tuesday, etc.
* Every X Week(s): e.g. every 2 weeks.

### Monthly

* Select Week of Month + Day of Week:  
   * e.g. Second Wednesday of each month.
* Or Action Date → same day-of-month as enrollment (e.g. 15th).
* Every X Month(s): e.g. every 1 month.

### Yearly

* Select Month + Day: e.g. July 1.
* Every X Year(s): e.g. 1 (annual billing).

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398102/original/npHprZub6XACVulhAKepOYGKTIb7qpINuw.png?1750162733)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398098/original/ahKeP8uBEa5FEcBgGYeN4LJLV5vtNdyzHQ.png?1750162733)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398101/original/0i8VvrLbemxjRtaW_mPpDs47avQJ9-VM3Q.png?1750162733)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398105/original/FKuiiG8ebpdu7py4y2lDNZW05IxPHKeNOg.png?1750162734)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398103/original/HDXv1onzXt1KCybckF3i-9aHft-ZSkuV6A.png?1750162734)

##   

## 6\. Enable Auto-Payment (Optional)

Toggle Enable Auto-Payment on if you want to automatically charge the customer’s saved card after the first successful payment. This is ideal for multi-payment subscriptions.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048398104/original/57DmYl0o-8LMKW0H64YfQJ9UN7YYBGRqQg.png?1750162734)

---

## 7\. Save, Test & Publish

1. Click Save in the upper-right corner.
2. Use Test Workflow to simulate enrollment and verify invoice timing.
3. Toggle Publish to activate.

  