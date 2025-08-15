**Date Updated:** 2024-12-16T22:48:23.000Z

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Action Name](#Action-Name)
* [Action Description](#Action-Description)
* [Action Details](#Action-Details)  
   * [Step-by-Step Guide](#Step-by-Step-Guide)
* [Action Settings](#Action-Settings)  
   * [Receive An Email](#Receive-An-Email)  
         * [Usage Cases:](#Usage-Cases%3A)  
         * [Receive an Email FAQs:](#Receive-an-Email-FAQs%3A)  
   * [Clicked a Trigger Link](#Clicked-a-Trigger-Link)  
         * [Usage Cases:](#Usage-Cases%3A-1)  
         * [Click a Trigger Link FAQs:](#Click-a-Trigger-Link-FAQs%3A)  
   * [Contact Tags Add or Remove](#Contact-Tags-Add-or-Remove)  
         * [Usage Cases:](#Usage-Cases%3A-2)  
         * [Contact Tags Add or Remove FAQs:](#Contact-Tags-Add-or-Remove-FAQs%3A)  
   * [Appointment Status](#Appointment-Status)  
         * [Usage Cases:](#Usage-Cases%3A-4)  
         * [Appointment Status FAQs](#Appointment-Status-FAQs)

---

## **Overview**

  
The   **Goal Event** enables you to set specific goals for the contact (ex: clicking a link). From the moment a contact enters the workflow, the system will "listen" for the specified Goal Event to occur regardless of the contact's step. Whenever the contact meets the defined goal, this action can automatically adjust the workflow by **skipping steps, waiting at the goal step, or ending the workflow**. 

  
## **Action Name**

  
 Goal Event

---

## **Action Description**

  
The Goal Event action allows you to define and track specific objectives within a workflow. When a contact achieves the goal, the system can automatically move them to a designated step, skip actions, or end the workflow. This feature helps streamline processes by making the automation more intelligently focused on key objectives, ensuring contacts are handled appropriately based on their interactions.

  
**Supported Goal Events:**

* **Email Events:** Such as opened, clicked, unsubscribed, etc.
* **Trigger Link Clicks:** Detects when a contact clicks a specific link.
* **Contact Tags:** Reacts when tags are added or removed from a contact.
* **Appointment Status:** Tracks changes in appointment statuses like new, confirmed, or showed.

---

## **Action Details**

  
### Step-by-Step Guide

1. **Choose the Action Type:** Select "Goal Event" from the list of available actions within the workflow builder.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155038184903/original/2EwIbMAqJjFvKkIblQJ9rGRTjlIol-q0Sw.png?1733969627)
2. **Name Your Action:** Enter a descriptive name, such as "Lead Conversion Goal."
3. **Select the Goal Event:** Choose the type of event that will trigger the goal. Supported events include:  
   * **Email Events:** Such as when a contact opens, clicks, or unsubscribes from an email.  
   * **Trigger Link Click:** When a contact clicks a specific link in your communications.  
   * **Contact Tags:** When a specific tag is added or removed from a contact.  
   * **Appointment Status:** When an appointment status changes to new, confirmed, or showed.  
         
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155038184917/original/YqKSn2HyyODQoZ8ejLSF2F7_tPhnu59IJA.png?1733969699)
4. **Define the Goal Criteria:** Specify the exact conditions that need to be met for the goal to be achieved. For example, if using email events, you might set the goal to trigger when a contact clicks a specific email link.
5. **Determine Workflow Response:** Decide what should happen when the goal is met:  
   * **Move to Next Step:** Continue the workflow from the next defined action.  
   * **Skip Steps:** Bypass certain actions and move directly to a specified step.  
   * **End Workflow:** Conclude the workflow if the goal is the final objective.
6. **Handle Unmet Goal Conditions:** Choose how to proceed if a contact reaches the goal step without meeting the goal:  
   * **End the Workflow:** Stop the workflow entirely.  
   * **Continue Anyway:** Proceed with the workflow even if the goal is unmet.  
   * **Wait Until Goal is Met:** Pause the workflow until the contact meets the goal.  
   * **Save and Activate:** After configuring the goal and its responses, save and activate the workflow to start monitoring contacts as they progress toward the goal.  
         
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155032404638/original/5ELF_3nLu0sC1iq017tdCGCWafC4Q16YVw.png?1725625147)

---

## **Action Settings**

  
### Receive An Email

  
For the "**Received email event**" filter, make sure to select the events you wish the system to recognize. There are several options:

* Clicked
* Opened
* Unsubscribed (Mailgun only)
* Complained
* Spam

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155038184984/original/RNvuVYprqmOWPbIeRnUqn7MNZHRq230eag.png?1733969933)

  
#### **Usage Cases:**

* **Engagement-Based Marketing:** Automatically move contacts to a workflow step designed for engaged users when they open or click on an email.
* **Drip Email Campaigns:** Move contacts to the next email in a drip series only after they've opened the previous one.
* **Unsubscription Handling:** Trigger a win-back workflow when a contact unsubscribes from your emails.
* Behavior-Based Personalization: If a contact clicks on a particular type of content in your emails more often (e.g., "Tech Gadgets"), trigger a workflow that sends them more personalized content based on their interests.
* **Event Registration:** If you're promoting an event via email, set a goal for when a contact opens the event invitation and triggers a follow-up workflow to nudge them toward registration.
* **Webinar Follow-up:** After sending a webinar replay link via email, trigger a follow-up workflow when a contact opens the email containing the replay.
* **Survey Participation:** Send out a survey via email and set a goal for when a contact opens the survey email, triggering a workflow to send them a thank you message or reward for participating.
* **Email Course Completion:** If you're delivering an email course, trigger a workflow that sends a certificate or badge when a contact opens the final course email.
* **Discount Usage:** If you've sent an email with a discount code, set a goal for when a contact opens the discount email, triggering a workflow to remind them to use their discount before it expires.
* **Sales Follow-up:** For sales teams, if a proposal or quotation is sent via email, set a goal for when the contact opens the email, triggering a follow-up workflow to keep the deal moving.

####   

#### **Receive an Email FAQs:**

**Can a single email event meet multiple goal events?**

  
Yes, a single email event, such as opening an email, can meet multiple goal events if the goals are set for that particular event.

  
**What if an email event happens outside of business hours? Will it still trigger the goal event?**

  
Yes, the system "listens" for the specified email event around the clock. The contact will be moved to the goal step if the goal event is met, even outside business hours.

  
**If a contact opens an email multiple times, will it trigger the goal event each time?**

  
No, once a contact meets a particular Email Event Goal, they won't be evaluated for the same goal event again in that workflow.

  
**What happens if an Email Event Goal is set for an email not part of the workflow?**

  
The goal event will only be triggered if the contact opens or clicks on the specific email associated with the goal while in the workflow. The goal event cannot be met if the email isn't part of the workflow.

  
**Can I set up a goal event when a contact does NOT open an email or click a link?**

  
Goal events currently support positive conditions, i.e., when a contact takes a certain action. Negative conditions, such as not opening an email, are not currently supported for goal events. You could set a wait step before the goal event that does something if the wait step expires without the goal being triggered, or you could make a different workflow that checks for the goal and does something if it hasn't happened.

  
### Clicked a Trigger Link

  
For the "**Clicked Trigger link,**" please select the trigger links listed in the dropdown menu. If you have not created a trigger link, please check out this article before continuing: [Trigger Links - Overview](https://help.gohighlevel.com/en/support/solutions/articles/48000981404).

  
#### ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155038185025/original/SMP0P7PB9j1l0_2R6HF77avOIvp1cjH46Q.png?1733970158)**Usage Cases:**

* **Website Engagement** **:** Move contacts to a workflow step designed for engaged users when they click on a specific link on your website.
* **Survey Responses:** Use different trigger links for different survey responses, moving the contact to a tailored workflow step based on their response.
* **Product Interest:** Move contacts to a workflow designed to nurture interest in a specific product or service when they click a link related to that product.
* **Content Marketing:** If you've shared a blog post or a guide, set a goal event for when a contact clicks the link to the content, triggering a follow-up workflow to gauge their interest or gather feedback.
* **Webinar Signups:** If promoting a webinar, trigger a follow-up workflow when a contact clicks on the registration link.
* **eCommerce Purchase:** If you're an eCommerce business, trigger a post-purchase workflow when a contact clicks on a "Buy Now" or "Add to Cart" link.
* **Membership or Subscription Signups:** If you're promoting a membership or subscription, trigger a welcome workflow when a contact clicks the signup link.
* **Trial Activation:** For software companies offering a free trial, trigger an onboarding workflow when a contact clicks on the "Activate Trial" link.
* **Affiliate Marketing:** If you're an affiliate marketer, trigger a follow-up workflow when a contact clicks on your affiliate link.
* **Download Confirmation:** If you're offering a free resource download, set a goal event for when a contact clicks the download link, triggering a follow-up workflow to engage the contact further.

####   
**Click a Trigger Link FAQs:**

**What if a contact clicks the trigger link before they enter the workflow? Will it still trigger the goal event?**

  
No, a contact needs to be in the workflow and meet the goal conditions during that time for the Trigger Link Clicked Goal Event to be activated.

  
**If a contact clicks a trigger link multiple times, will it trigger the goal event each time?**

  
No, once a contact meets a particular Trigger Link Clicked Goal Event, they won't be evaluated for the same goal event again in that workflow.

  
**What happens if a contact clicks a trigger link but does not meet other conditions for the Goal Event?**

  
The contact will not be moved to the Goal Event step unless they meet all conditions set for that goal event.

  
**Can a trigger link from any website be used for the Trigger Link Clicked Goal Event?**

  
The trigger link needs to be a tracked link from your email marketing or automation platform for the system to detect the click and trigger the Goal Event.

  
**Can I use the same trigger link for different goal events in the same workflow?**

  
Yes, you can use the same trigger link for different goal events, provided each goal event has unique conditions.

  
### Contact Tags Add or Remove

  
* Contact Tag **Added** — Contact gets pulled to the goal step when a specified tag gets added.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155038185048/original/1RGHb25Okf7f197QfEHFN33P1zGTmk65hg.png?1733970278)
* Contact Tag **Removed** — Contact gets pulled to the goal step when a specified tag gets removed.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155038185047/original/BTwnprUlBg8uBZpGB78SKETPckxu6AvuOQ.png?1733970276)

  
**Example using the Tag Goal action in a workflow:**  
  
Let's say I am trying to sell a product, and as soon as the product purchase is completed, I want to add the tag “**product purchased**” to the contact. Meanwhile, I want to keep the contact in the nurture workflow. As soon as the "**product purchased**" tag is added to the contact, I want to stop the nurturing workflow and remove the contact.

  
The system already has the capability to do this using a different trigger in a different workflow, but the addition of the **Goal Event Action** \> **Tag function** eliminates the requirement for a 2nd workflow.

  
Just add a Goal Step at the end of the workflow with the goal event as - contact tag added - “**product purchased."**

  
The contact will be pulled forward to the goal step and continue once the tag is added. In this case, since it's the last step, the workflow would end and remove the contact.

  
#### **Usage Cases:**

* **Sales Funnel Management:** Automatically move contacts through different stages in your sales workflow as they progress from "Lead" to "Prospect" to "Negotiation" to "Closed Won".
* **Product Purchase:** Use a Goal Event to trigger a post-purchase follow-up or upselling workflow when a "Product Purchased" tag is added to a contact.
* **Engagement Level Tracking:** Use Tag Goal Events to move contacts between workflows designed for different engagement levels, using tags like "High Engagement" or "Low Engagement".
* **Subscription Status:** Trigger different workflows for retention or win-back strategies based on changes in a contact's subscription status, signified by "Subscribed" or "Unsubscribed" tags.
* **Behavioral Segmentation:** Use tags to segment your contacts based on behaviors like "Downloaded E-book" or "Attended Webinar" and trigger workflows tailored to these actions.
* **Customer Satisfaction:** Use tags to denote customer satisfaction levels gathered from surveys or feedback forms and trigger workflows for customer retention or damage control.
* **Event Attendance:** Trigger post-event follow-ups or offer special deals to contacts who attended a particular event, tracked by tags like "Attended Event X".
* **Referral Program:** If you're running a referral program, add a "Referrer" tag to contacts who refer others and trigger a workflow for special thank you messages or rewards.
* **Upsell/Cross-sell:** If a customer purchases a particular product or service, a specific tag could be added that triggers a workflow designed to upsell or cross-sell related products or services.
* **Trial Users:** For software or subscription-based services, add a "Trial User" tag to contacts on a free trial and trigger a workflow designed to convert these trials into paid subscriptions.

####   

#### **Contact Tags Add or Remove FAQs:**

**How can I track if a tag was added or removed externally, outside the workflow?**

  
Yes, the system "listens" for any changes to a contact's tags, irrespective of where that change comes from, and will trigger the Goal Event accordingly.  
  
**What if I want to change the goal tag after some contacts have already entered the workflow?**

  
Changing the goal tag will not affect the contacts already entering the workflow. Only the contacts entering the workflow after the change will be evaluated against the new goal tag.  
  
**Can I use the same tag for different goal events in the same workflow?**

You can have separate goal events for adding and removing the same tag. Remember that contacts will be pulled to the goal step when they meet the goal condition.  
  
**Can a contact meet the same Tag Goal Event more than once in the same workflow?**

No, once a contact is pulled to the goal step after meeting a Tag Goal Event, they won't be evaluated for the same goal event again in that workflow unless the tag is removed from the contact and added to it again while the contact is in the same workflow.  
  
**How can I use tags to track changes in a contact's lifecycle stage and automate the corresponding workflow?**

  
You can assign tags corresponding to different lifecycle stages, such as "Lead", "Prospect", and "Customer", and set up goal events in your workflows for these tags. The system automatically moves contacts to the appropriate step as their stage changes.

  
### Appointment Status

  
For Appointment Status, please select a Calendar from the dropdown menu and then select one or more of the New, Confirmed, and Showed appointment statuses.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155038185081/original/Kq_JMdxVbRIL6tppkPQdwt10grzF7GjzmA.png?1733970458)

* **New** — Contact gets pulled to the goal step when the appointment status of the selected calendar changes to "New".
* **Confirmed** — Contact gets pulled to the goal step when the appointment status of the selected calendar changes to "Confirmed".
* **Showed** — Contact gets pulled to the goal step when the appointment status of the selected calendar changes to "Showed".

  
#### **Usage Cases:**

* **Client Onboarding:** Suppose you have a workflow for onboarding new clients, and part of that process is scheduling an introductory meeting. The "Confirmed" appointment status can be a goal event. Once the appointment is confirmed, the contact could skip to the next phase in the onboarding process.
* **Sales Funnel:** In a sales process, you could set up a workflow where a "New" appointment status acts as a goal event. When potential customer books an initial consultation, they automatically move further down the sales funnel, bypassing initial engagement or outreach steps.
* **Class or Webinar Sign-ups:** A workflow could be set up for an educational platform or webinar host where a "Showed" appointment status for a Class Calendar is the goal event. When a student or participant attends a class or webinar (indicating their appointment status as "Showed"), they could be automatically moved to a follow-up step in the workflow, such as receiving additional learning resources or being asked for feedback.
* **Product Demonstrations:** A workflow could be set up for a company offering product demos where a "New" or "Confirmed" appointment status for a demo is a goal event. Once a customer books or confirms a demo, they could be moved to the next stage in the customer journey, such as receiving preparation materials for the demo.
* **Healthcare Appointments:** Patient follow-ups could be a workflow in a healthcare setting. Once a patient's appointment status is set to "Showed," indicating they attended their initial appointment, the workflow could move them to a goal step where they receive a follow-up survey or reminder for their next appointment.
* **Fitness or Personal Training Sessions:** If you run a fitness studio or personal training service, you might set up a workflow where a "Showed" appointment status for a personal training session acts as a goal event. When clients attend their session, they could be automatically moved to a step in the workflow where they receive a follow-up email with a workout summary or a discount offer for booking their next session.
* **Real Estate Showings:** A workflow could be set up for a real estate agent where a "Showed" appointment status for a property viewing is a goal event. Once prospective buyers view a property, they could be moved to a step in the workflow where they receive further details about the property, mortgage information, or other listings they might be interested in.
* **Customer Support or Service Appointments:** If your organization provides customer support or services that require appointments, you could set up a workflow where a "Confirmed" or "Showed" appointment status acts as a goal event. When customers confirm an appointment or show up for their scheduled service, they could be moved to the next step in the workflow, receiving a customer satisfaction survey or a reminder for their next service appointment.
* **Consulting or Coaching Services:** If you're a consultant or coach, a "Confirmed" appointment status for a consulting session could be the goal event in your workflow. Once clients confirm a session, they could be moved to a step where they receive preparatory materials or questions to consider before the session.
* **Interview Process for HR:** In a human resources context, you could have a workflow where a "Showed" appointment status for an interview acts as a goal event. When a candidate attends the interview, the workflow could move them to the next step, such as a background check or receiving a feedback survey about the interview process.

  
#### **Appointment Status FAQs**

  
**How does the system handle multiple contacts meeting the Appointment Goal Event simultaneously?**

  
The system is designed to handle multiple contacts meeting the goal conditions simultaneously. Each contact will be moved to the corresponding goal step in the workflow independently of the others.

  
**What happens if a contact's appointment status changes while they are in the middle of a different step in the workflow?**

  
If the change in appointment status matches the conditions for a Goal Event, the system will automatically pull the contact into the goal step, regardless of their current position in the workflow.

  
**How can I use Appointment Goal Events to improve my sales or booking process?**

  
Appointment Goal Events can help automate and streamline your sales or booking process by moving contacts to appropriate steps based on their actions. For example, if a contact confirms an appointment, you can automatically move them to a step where they receive preparation materials.

  
**Can the Appointment Goal Event handle changes to appointment status made outside of the workflow, like manual updates?**

  
Yes, the system will "listen" for the specified Goal Event to occur, regardless of where the change in appointment status comes from. Whether the status is changed by another part of the workflow, an external system, or a manual update, the contact will be moved to the goal step if the conditions are met.

  
**What if an appointment is rescheduled or canceled after a contact has already been moved to the goal step in the workflow?**

  
The movement to the goal step is based on the conditions when the Goal Event was detected. If the appointment status changes after the contact has been moved to the goal step, it will not reverse the action. You may need to handle such situations with additional workflows or manual interventions.

  
**Can I use Appointment Goal Events in conjunction with other types of Goal Events in the same workflow?**

  
Yes, you can use multiple types of Goal Events in the same workflow. However, remember that each Goal Event operates independently, so contacts will be moved to the step associated with each Event as soon as they meet the conditions, regardless of the other Goal Events.

  