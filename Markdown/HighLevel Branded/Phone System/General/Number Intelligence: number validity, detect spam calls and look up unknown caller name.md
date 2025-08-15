**Date Updated:** 2025-04-29T19:40:47.000Z

Number Intelligence is a bundle of best-practice phone number checks. It ensures that using the phone for calls and texts works as expected, keeps costs under control, and protects reputation.

---

**TABLE OF CONTENTS**

* [What Is Number Intelligence](#What-Is-Number-Intelligence)
* [Benefits of Number Intelligence](#Benefits-of-Number-Intelligence)
* [How to Enable or Disable Number Intelligence](#How-to-Enable-or-Disable-Number-Intelligence)
* [Number Intelligence Pricing](#Number-Intelligence-Pricing)
* [Call Handling with Spam Detection](#Call-Handling-with-Spam-Detection)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

## **What Is Number Intelligence**

  
Number Intelligence is a bundle of functions that clarify details about how phone calls and SMS are expected to work:

* **Spam Detection:** detects and flags risky incoming calls from unknown USA numbers. If flagged, calls are tagged as “Spam Likely” in call logs and conversations. This information can be used in automations and by your team to improve operations.
* **Name Lookup:** fetches the name of unknown USA callers. With the caller name the CRM will have complete records and your team can personalize call handling.
* **Number Validation:** verifies the validity of a number worldwide before sending the first SMS to ensure deliverability. Validation is only performed when an SMS is queued before sending, not during Contact Import/Creation. If the number is identified as a landline number, we will not send even the first message to the carriers.

---

## **Benefits of Number Intelligence**

  
* **Reduce wasted time** because your team won't respond to spam calls.
* **Increase call answer rates** by redirecting your team's attention from spam calls to real calls.
* **Improve customer satisfaction** by greeting incoming leads with their name.
* **Increase SMS delivery rate** and maintain healthy metrics by ensuring messages are only sent to valid numbers.

  
---

## **How to Enable or Disable Number Intelligence**

  
To enable or disable Number Intelligence on the web app, go to Settings > Phone Numbers > Advanced Settings > Number Intelligence. Toggle the switch to enable or disable the feature. When enabled, **all three components are activated/deactivated together**.
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155037843831/original/akHzXuztsYanBhBsWVlinDTVUZb9X4rygA.png?1733424186)

  
---

## **Number Intelligence Pricing**

  
Number Intelligence is charged to the Agency Wallet at these prices. The Subaccount wallet is charged according to the SaaS Rebilling you setup.

  
* **Spam Detection:** $0.005 per call from unknown U.S. numbers. This checks all incoming calls from unknown USA numbers. "Unknown" means the number is not saved to a contact.
* **Name Lookup:** $0.01 per call from unknown U.S. numbers. This looks up the name for all incoming calls from unknown USA numbers. "Unknown" means the number is not saved to a contact that has a completed name field. So this will trigger when the number is not saved OR when it is a contact but the name field is empty.
* **Number Validation:** $0.005 per validation. This applies to all numbers worldwide and is not charged when the phone number is added to the contact but before the first SMS is sent. If it fails, the SMS is not sent.

  
---

  
## **Call Handling with Spam Detection**

  
Incoming calls that fail Spam Detection are marked “Spam Likely” on the web dialer when you receive the call and shown with a tag in the Contacts tab for transparency.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155037834499/original/DPOZ1lBojoeHqHEG3SzqyjtLwv181zY5-A.png?1733413915)

  
---

## **Frequently Asked Questions**

  
**Q: What happens if I disable Number Intelligence?**

When disabled, spam calls, name lookups, and SMS validations will no longer be performed. Calls and SMS will proceed as usual, but spam may not be flagged, names on unknown callers will not show up. SMS delivery rate may reduce because you may end up trying to send SMS to phone numbers incapable of receiving SMS.

  
**Q: Can I customize which features of Number Intelligence are enabled?**

As of Dec 5th, 2024, all three features (Spam Detection, Name Lookup, and Number Validation) are activated or deactivated together.

  
**Q: Does this feature work outside USA?**

Spam Detection and Name lookup currently applies only to calls from phone numbers from USA. The location of the sub-account or their phone number does not matter. SMS validation works worldwide.

  
**Q: How does the system handle spam calls?**

Spam calls are flagged as “Spam Likely” and can still appear in call logs and conversations. You can later add these numbers to an inbound DND list for further blocking.

  
**Q: Will I be notified of spam calls?**

Yes, spam calls will appear in your call logs and the Contacts tab, tagged as “Spam Likely.”