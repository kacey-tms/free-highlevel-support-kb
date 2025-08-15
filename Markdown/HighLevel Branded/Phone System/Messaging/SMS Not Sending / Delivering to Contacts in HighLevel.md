**Date Updated:** 2025-06-10T16:53:44.000Z

  
It’s frustrating when a text never arrives—whether it’s an appointment reminder, a promotion, or a two-way chat. This guide walks you through each step of our delivery pipeline, shows you where things can go wrong, and gives you clear, actionable fixes so you can get back on track fast.

---

**TABLE OF CONTENTS**

* [How Message Delivery Works](#How-Message-Delivery-Works)
* [Where to Find Error Messages in HighLevel](#Where-to-Find-Error-Messages-in-HighLevel)
* [Common Reasons Why Messages Fail (And How to Fix Them)](#Common-Reasons-Why-Messages-Fail-%28And-How-to-Fix-Them%29)  
      * [At the HighLevel Layer](#At-the-HighLevel-Layer)  
      * [At the Twilio/LC Phone Layer](#At-the-Twilio/LC-Phone-Layer)  
      * [At Sender Carrier Network Layer](#At-Sender-Carrier-Network-Layer)
* [Super-Quick Checklist Before You Click “Send”](#Super-Quick-Checklist-Before-You-Click-%E2%80%9CSend%E2%80%9D)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

  
# How Message Delivery Works

When you send a message from HighLevel, it travels through multiple layers:

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047990043/original/rtRKVPSokDhZTTns4Bqu6AbZhQHdt-PEfA.jpeg?1749549338)

  
If the message fails at any layer, it may not be delivered to the end user. Let's look at how to spot these issues and fix them.

---

# Where to Find Error Messages in HighLevel

If your message didn’t go through, check the Conversations View. In most cases, when a message fails to send or deliver, we display an error in the conversation view that appears like this:  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047990199/original/P_8HI4w-CK0Bdls-2tuEDfhrZBM2G04fAw.png?1749549430)

The error message and error code will provide you with clues about what is going wrong and how to proceed from there.

---

# Common Reasons Why Messages Fail (And How to Fix Them?)

  
### At the HighLevel Layer

  
| Issue                                                                     | Cause                                                                                                                                                                                                                                  | Fix (Help docs)                                                                                                                                                                                                    |
| ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Contact has DND (Do Not Disturb) Enabled                                  | When DND is enabled for a contact on the message channel or overall, HighLevel doesn't send the message and displays an error in the conversation screen.                                                                              | Remove DND status from the contact to resume message sending.➡️ [DoNotDisturb DND](https://help.gohighlevel.com/support/solutions/articles/48001214849)                                                            |
| The Number Is a Landline                                                  | When number validation is enabled, the system checks if a number is message-capable (i.e., not a landline). If not, it prevents the message from being sent.                                                                           | Use a mobile number instead or disable number validation if necessary.➡️ [Number Intelligence](https://help.gohighlevel.com/en/support/solutions/articles/48001153968)                                             |
| Sub-Account is New and Undergoing Ramped Sending                          | HighLevel restricts message volume for new sub-accounts to prevent spam, gradually increasing limits over time.                                                                                                                        | Wait for limits to increase automatically, or have the agency request a lift.➡️ [LC Phone Messaging Policy (check Ramp-Up Model: section)](https://help.gohighlevel.com/en/support/solutions/articles/48001213941) |
| Sub-Account Has Hit Its Daily Message Limit                               | Each sub-account has a daily message limit set by the agency. Bulk and automated messages stop sending once this limit is hit, but individual replies can still be sent. Agencies have control over these limits for each sub-account. | Adjust daily limits from the agency settings, or wait until the next day.➡️ [LC Phone Messaging Policy](https://help.gohighlevel.com/en/support/solutions/articles/48001213941)                                    |
| Sub-Account Sending Suspended Due to High Errors, Opt-Outs, or Complaints | Sub-accounts exceeding spam, opt-out, or carrier complaint thresholds have message sending suspended. Attempts to send messages during suspension will be skipped and display an error.                                                | Follow deliverability best practices and contact support if needed.➡️ [Best Practices for Deliverability](https://help.gohighlevel.com/support/solutions/articles/155000000079)                                    |
  
  
### At the Twilio/LC Phone Layer

  
| ? Error                        | Cause                                                                                                                                  | Fix                                                                                             |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Number is on Twilio's DND list | The number is on Twilio’s DND list due to a previous opt-out or carrier complaint. Messages will fail unless the contact opts back in. | The contact must text “START” to the same Twilio number to re-enable messaging.                 |
| 30001: Queue Overflow          | Messages are queued based on the sender’s or account’s rate. If they stay in the queue for over 4 hours, they fail.                    | Reduce the Validity Period in Messaging Service settings or API requests to shorten queue time. |
| 30002: Suspended Sub-Account   | Message fails if the Twilio sub-account is suspended between queuing and sending.                                                      | Contact Twilio or HighLevel Support to resolve the suspension.                                  |

###   

  
### At Sender Carrier Network Layer  

  
| Error                                  | Cause                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Fix                                                                                                                |
| -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| 30003: Unreachable Destination Handset | The recipient's phone may be off, have no signal, be a landline, or there may be a mobile carrier issue.                                                                                                                                                                                                                                                                                                                                                                               | Retry later or verify the number is a mobile line and properly reachable.                                          |
| 30004: Message Blocked                 | Possible reasons messages might not be sent or delivered to contacts include: The destination number is blocked, the device has insufficient signal or cannot receive message (e.g., landline), the number is on India's Do Not Call registry, there's a mobile carrier issue, or a US/CA toll-free number was sent to a handset that previously opted out.                                                                                                                            | Ensure the number is valid and opted in. Avoid sending to DND or blocked numbers.                                  |
| Attachment File Too Large              | The file size exceeds carrier limits for MMS.                                                                                                                                                                                                                                                                                                                                                                                                                                          | ➡️ [File Size Limits for Attachments in SMS.](https://help.gohighlevel.com/support/solutions/articles/48001208913) |
| International Geo Permissions          | Your account might not have permission to send international messages..                                                                                                                                                                                                                                                                                                                                                                                                                | Contact support.                                                                                                   |
| Message Body Too Long                  | \- If you are using a trigger to send a message. Check the body of the message. Also, check to see if there is a custom value of {{message.body}}\- For example, if someone replies via email and their email exceed the limit of 1600 characters, the message will not send if you have the custom value {{message.body}}![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047990631/original/PvnlWbqLsSDvP46SqUbwxdC7wgjSuYDhkQ.png?1749549640) | Trim the message manually or modify the trigger logic to exclude large custom values.                              |

  
---

# Super-Quick Checklist Before You Click “Send”

  
✅ Check Conversations: Note any red error badge.  
  
✅ Match Error Code: Use the tables above to find cause.  
  
✅ Apply Fix: Follow the “Fix” column for that issue.  
  
✅ Retry: Resend the message after adjustments.  
  
✅ Monitor: Confirm delivery or note a new error code

---

# Frequently Asked Questions

  
**Q: Why am I getting charged for failed message messages?**A: Charges apply once an message is attempted—even if it fails later in the process.

**Q: How do I know exactly why a message failed?**A: You can check the message logs in Twilio.  
➡️ [How to check Twilio logs](https://help.gohighlevel.com/en/support/solutions/articles/48001222601)

---

# **Related Articles**

* [](https://help.gohighlevel.com/en/support/solutions/articles/155000002369)[Best Practices for SMS deliverability and Avoiding SMS Restrictions](https://help.gohighlevel.com/en/support/solutions/articles/155000000079)
* [LC - Phone Messaging Policy](https://help.gohighlevel.com/en/support/solutions/articles/48001213941)
* [SMS / Phone number Validation](https://help.gohighlevel.com/en/support/solutions/articles/48001153968)
  
  