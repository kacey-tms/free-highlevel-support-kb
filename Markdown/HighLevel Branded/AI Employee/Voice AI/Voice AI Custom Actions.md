**Date Updated:** 2025-06-11T13:42:59.000Z

This article will show you how to use Voice AI Custom Actions to enable real-time webhook integrations during live calls. This powerful feature allows your AI agents to interact with external systems mid-conversation—pulling data, executing processes, and improving automation without waiting until after the call ends.

  
**TABLE OF CONTENTS**

* [What is Voice AI Custom Actions?](#What-is-Voice-AI-Custom-Actions?)
* [Key Benefits of Custom Actions](#Key-Benefits-of-Custom-Actions)
* [How to Set Up Custom Actions in Voice AI](#How-to-Set-Up-Custom-Actions-in-Voice-AI)
* [Webhook Integration](#Webhook-Integration)
* [Conversation Triggers](#Conversation-Triggers)
* [Dynamic Parameter Collection](#Dynamic-Parameter-Collection)
* [Real-time Testing](#Real-time-Testing)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What is Voice AI Custom Actions?**

  
Voice AI Custom Actions allow AI agents to trigger custom POST webhook calls to external APIs during a live conversation. These actions can include authentication, headers, and dynamic parameters collected in real-time from the call. This enables agents to retrieve or send information instantly based on what the caller says.

  
## **Key Benefits of Custom Actions**

  
Voice AI Custom Actions enable seamless integrations with external systems directly within a live call. This enhances the agent’s ability to personalize and resolve issues faster.

* Perform real-time API calls triggered by conversation cues.
* Automate data lookups or submissions mid-call. For example, if a customer asks, “What’s the status of my recent order?”, the AI can instantly call your order management system and retrieve the real-time status—without putting the caller on hold.
* Configure POST requests with authentication and headers.
* Dynamically pass call data (like phone numbers or order IDs).
* Test webhook responses before going live.
* Reduce follow-up tasks by resolving needs during the call.

---

## **How to Set Up Custom Actions in Voice AI**

  
Voice AI Custom Actions can be configured from the Voice AI Labs interface with just a few steps.

  
Here’s how to get started:

1. Navigate to **Labs > Voice AI > Custom Actions**.
2. Click **Create Action** to open the configuration window.
3. Enter a name and description for the action.
4. Add your **Webhook URL** and select **POST** as the method.
5. Enter any required **authentication** details (e.g., Bearer token).
6. Add any custom **headers** as needed.
7. Define **parameters** dynamically pulled from the conversation.
8. Set **conversation trigger conditions**  For instance, if your AI assistant needs to retrieve a user’s account balance after they say “check my balance”, you can set a trigger with that phrase and define a parameter for their phone number to pass into your banking API.
9. Use the **Test Webhook** feature to validate the setup.
10. Click **Save** to activate the custom action.

---

## **Webhook Integration**

  
Webhook integration is the core of Voice AI Custom Actions. It allows your agents to interact with any external system that supports APIs—CRM, scheduling tools, databases, and more.

  
Each Custom Action is defined by a POST request, which may include:

* A webhook endpoint URL.
* Headers (e.g., API keys, tokens).
* A request body with dynamic parameters.
* Authentication (Bearer token, Basic Auth, etc.).

  
**Example:** If you’re integrating with a CRM like Salesforce, your webhook URL might target an endpoint like /api/v1/lookupContact and include parameters like the contact’s email or phone number.

---

## **Conversation Triggers**

  
Triggers define the conditions under which a Custom Action is executed during the call. You can create simple phrase-based triggers or configure more complex logic.

  
Example triggers:

* When a user says: “I want to check my appointment.”
* When an email is mentioned.
* When a string of digits (e.g., order number) is spoken.

  
Triggers can also be layered with **conditions** like “only run if parameter X is present.”

---

## **Dynamic Parameter Collection**

  
Voice AI can extract and label relevant data in real time during conversations. These values are automatically assigned to parameters used in the webhook request. This is useful when, for example, the AI needs to extract both an order number and an email address before triggering a shipping status lookup. You can assign these extracted values to your webhook payload, ensuring the integration is context-aware and personalized.

  
Supported data types:

* Text (String)
* Number (Numeric)
* Email
* Phone Number
* Date (coming soon)

  
You can assign these values to any part of your webhook payload to customize your integration.

  
## **Real-time Testing**

  
Before saving a Custom Action, you can use the built-in **Test Webhook** tool. This allows you to simulate a call scenario, pass test data, and view the response from your external system in real time. You can use the test tool to mimic a customer asking to “reschedule an appointment” and check whether the webhook correctly pulls and sends the provided date and time to your calendar system.

  
You’ll be able to:

* See the full request (headers + body).
* View the raw response (200 OK, 404 Not Found, etc.). Example, If your webhook response includes an estimated delivery date, your AI agent can immediately inform the caller: “Your package is expected to arrive by Thursday.”
* Identify and fix misconfigurations before saving.

---

## **Frequently Asked Questions**

  
**Q: Can I use GET or other request types?**

No, only POST requests are currently supported for Custom Actions.

  
**Q: Where do I access Voice AI Custom Actions?**

You can access it under **Labs > Voice AI > Custom Actions** once Labs is enabled in your account.

  
**Q: Is authentication supported in webhooks?**

Yes, you can use Bearer tokens, Basic Auth, or pass keys in headers.

  
**Q: What if my webhook fails during the call?**

The system logs the failure, and fallback behavior can be defined if no data is returned or the webhook times out.

  
**Q: Can I trigger multiple webhooks during a single call?**

Yes. Each Custom Action can be triggered independently based on its own conditions.

  
**Q: Do I need a developer to set up these actions?**

Not necessarily. As long as you have access to the API documentation for the external system, you can set this up with minimal technical skills.