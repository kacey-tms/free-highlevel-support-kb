**Date Updated:** 2025-03-24T17:00:17.000Z

In this article we will be talking about the process of creating a workflow for sending back Conversion API action to Facebook and the newly added ad manager radio button under Facebook Conversion API action in workflows and what value does it add to the user.

---

## **TABLE OF CONTENTS**

  
* [Why do I need to create a CAPI action workflow after creating an ad campaign and conversion pixel?](#Why-do-I-need-to-create-a-CAPI-action-workflow-after-creating-an-ad-campaign-and-conversion-pixel?)
* [Which workflow triggers can be used with Facebook Conversion API action?](#Which-workflow-triggers-can-be-used-with-Facebook-Conversion-API-action?)
* [How is Ad Manager radio button different from Integrations radio button in the Facebook Conversion API action?](#How-is-Ad-Manager-radio-button-different-from-Integrations-radio-button-in-the-Facebook-Conversion-API-action?)
* [Can I use the offline events with trigger names like 'Call', 'opportunity change status', 'tag', etc. with Facebook Conversion API action?](#Can-I-use-the-offline-events-with-trigger-names-like-'Call',-'opportunity-change-status',-'tag',-etc.-with-Facebook-Conversion-API-action?)

  
---

## **Why do I need to create a CAPI action workflow after creating an ad campaign and conversion pixel?**

  
Creating and sending **CAPI (Conversions API)** events to Facebook after setting up your ad and pixel is important for enhancing the accuracy, reliability, and effectiveness of your Facebook advertising campaigns. Here’s why you need to use the CAPI in addition to the standard Facebook pixel:

  
* **Improved Accuracy**: CAPI sends data directly from your server, bypassing issues like browser restrictions, ad blockers, and cookie limitations, ensuring more reliable tracking of user actions.
* **Better Attribution**: It tracks conversions across devices and platforms (including users who block cookies), providing more complete data for campaign optimisation therefore accurate reporting.
* **Fills Pixel Gaps**: When pixel data is blocked or missed (e.g., due to slow load times or privacy settings), CAPI ensures those conversions are still recorded.
* **Enhanced Optimisation**: More granular, server-side data helps Facebook improve ad targeting and performance.
* **Privacy Compliance**: CAPI is better suited for privacy regulations as it reduces reliance on client-side cookies.
* **Efficient Budget Spend**: More accurate data allows Facebook to optimise your ad spend and improve return on investment (ROI).

  
In summary, sending back **CAPI events** to Facebook after creating your pixel is essential to improve the **accuracy** of your tracking, **optimise** your ads more effectively, and **enhance attribution** across devices and browsers. It fills in gaps left by browser-based pixel tracking and helps ensure that your ad campaigns are working as efficiently as possible, even with increasing privacy concerns and browser restrictions.

  
---

## **Which workflow triggers can be used with Facebook Conversion API action?**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155037638079/original/CL4W8FAhtV-LjEKe9VfqBVqFAUa_pIhS0A.png?1733217275)

  
In workflows, if your action is Facebook Conversion API, the triggers which can be used depend on the **Event Type** that you will be using in the FB CAPI action. All the eligible triggers for both lead and funnel events are listed as under:

1. For **Funnel events** in Facebook conversion API action, you can use the following triggers; Form Submitted, Survey Submitted, Customer Booked Appointment, and Order Form Submission.  
(For an appointment, it will only work with "Customer Booked appointment," not with "appointment," as appointments are the general triggers and "Customer Booked appointment" is the trigger for the widget)
2. For **Lead events** in Facebook conversion API action, you can only use the trigger "Facebook Lead Form Submission" and "Pipeline Stage Change"(This will work if your contact is coming from a Facebook lead form)

---

## **How is Ad Manager radio button different from Integrations radio button in the Facebook Conversion API action?**

  
During the creation of conversion API action under workflows, we see two connection type option:

* Integrations
* Ad Manager

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155037640699/original/XgEzH7KgUbwqwsE11_g8-9NOhFn2fjbNtg.png?1733218709)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155037642428/original/1iwxoBDshNInBgDVWRqYNhbg_m_Qipp2CA.png?1733219741)

  
**Note:** All the information with respect to the Integration connection type and the details of what each field under it means can be understood in detail by following the below two articles:[](https://help.gohighlevel.com/support/solutions/articles/48001233833-facebook-conversion-leads-walkthrough)  
[Facebook conversion leads walkthrough ](https://help.gohighlevel.com/support/solutions/articles/48001233833-facebook-conversion-leads-walkthrough)[](https://help.gohighlevel.com/support/solutions/articles/48001236281-how-to-set-up-a-funnel-event-pixel-for-facebook-conversion-api-)  
[Setup a funnel event for Facebook conversion API](https://help.gohighlevel.com/support/solutions/articles/48001236281-how-to-set-up-a-funnel-event-pixel-for-facebook-conversion-api-)

  
The addition of Ad Manager option as the connection type is mainly to ease the user flow and save the hassle of constant to and fro from Facebook to workflows. Below are the enlisted points on what efforts are minimised with the addition of it.

  
1. You can select the event type based on the campaign you want to send back CAPI to Facebook. If your campaign objective is 'Website traffic' send a funnel event and if it's 'Lead generation' then send a lead event.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155037642569/original/ti2vYHAvUK-6ccMIVPu3FfsPaaL1air54A.png?1733219814)
2. All the pixels that are part of Ad Manager will be pre-populated as the dropdown items giving you an option to select one from it. This saves you from the hassle of going back to Facebook and copy/paste the Pixel ID.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155037642910/original/r6PKw2USmYvjpzah_TJZiuYisNbIbeB78w.png?1733220060)
3. There is no need to generate and then add the access token to CAPI action when under Ad Manager connection type, we take care of it to again help you with the to and fro.
4. Stage name in a Lead Event refers to: It should accurately represent your Pipeline and Pipeline Stage name for better reporting. Select it using the tag icon at the end to add the custom value of the opportunity pipeline and stages.

  
---

## **Can I use the offline events with trigger names like 'Call', 'opportunity change status', 'tag', etc. with Facebook Conversion API action?**

  
Yes, it is possible to do so and we will be using the last possible pixel data to send this event. Basically, if the fbclid id is found, the data will be sent to conversion API. It can be best explained by the following examples:

  
**Example 1:** 

Contact created Facebook form submission, thus first attribution source will be Paid Social (Facebook). If you use workflow with Facebook form submitted trigger, the contact will have fbclid and workflow will send data to conversion API (CAPI).

  
Additional Behaviour -  
After sometime that contact got converted to opportunity with add/update opportunity trigger addition, you use opportunity status trigger in workflow to send the data to conversion api as contact from Facebook form submitted will pass fbclid.

  
**Example 2:** 

Contact created google ad, organic google search or direct traffic,, thus first attribution source will be Paid Search (Google) or Direct Traffic. If the contact after certain time interacted with Facebook form and they fill the form, the latest attribution will be Paid Social(Facebook) with contact having fbclid. Now, if the agency runs workflow with Facebook form submitted > Facebook conversion API, it will send the data to conversion API with fbclid.

  
Additional Behaviour - 

After sometime that contact got converted to opportunity with add/update opportunity trigger addition, you use opportunity status trigger in workflow to send the data to conversion api as contact from Facebook form submitted will pass fbclid.

  
---

**Please Note:**  
**Addition of Custom Values -**  
Similar to Google Ads, we are now allowing custom mapping for Facebook Ads conversion tracking parameters.  
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155043836459/original/gFVWuYxc77LoQwMEWkY0p_spdSoyA3QWZQ.jpeg?1742815441)  
  
  
**How It Works:**  
  
By default, custom mapping is disabled.  
Users can toggle it on to enable custom mapping.  
  
When enabled, users can map:  
1\. FBCLID for funnel events.  
2\. Facebook Lead ID for lead events.  
3\. If custom mapping fields are provided, they will take priority over system defaults.  
4\. If left empty, the system will continue using its default internal values.
  
  