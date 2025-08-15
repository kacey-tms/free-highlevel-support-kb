**Date Updated:** 2025-07-29T15:42:30.000Z

Create dynamic, personalized surveys in HighLevel with the new **Conditional Logic Feature**. This guide covers the what, why, and how of setting up conditional logic in HighLevel surveys, combining official documentation with hands-on tutorials.

  
**IMPORTANT** - This Feature is available only for newly created or cloned surveys. Conditional logic will not get transferred when we create a snapshot of the account.

---

**TABLE OF CONTENTS**

* [What Is Conditional Logic in Surveys?](#What-Is-Conditional-Logic-in-Surveys?)
* [Why Conditional Logic Matters](#Why-Conditional-Logic-Matters)
* [How to Access Conditional Logic in Surveys](#How-to-Access-Conditional-Logic-in-Surveys)
* [Available Conditional Logic Options](#Available-Conditional-Logic-Options)
* [Best Practices](#Best-Practices)
* [**Troubleshooting: Fields Not Appearing in Conditional Logic?**](#Troubleshooting%3A-Fields-Not-Appearing-in-Conditional-Logic?)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

---

## **What Is Conditional Logic in Surveys?**

  
Conditional Logic in Survey Builder allows you to set up rules that change the survey flow or content based on how users respond. By defining specific actions triggered by certain answers, you can personalize the survey journey, streamline data collection, and ensure only relevant questions are shown to each respondent. This feature is available for newly created or cloned surveys in HighLevel.

  
#### **Example Scenario:** Imagine you ask, “What’s your budget range?” If a user selects “Enterprise,” you might want to:

* Show an extra set of enterprise-specific questions.
* Skip over small-business slides entirely.
* Redirect qualified leads to a booking page.

---

## **Why Conditional Logic Matters**

Implementing conditional logic in your surveys helps you:

* **Personalize the experience:** Ask only relevant questions and keep respondents engaged.
* **Improve data quality:** Filter out or disqualify responses that don’t meet your criteria.
* **Shorten surveys:** Jump respondents past irrelevant sections to reduce abandonment.
* **Drive actions:** Redirect high-value leads to booking pages or custom thank-you screens.

---

## **How to Access Conditional Logic in Surveys**

Get started by opening your survey in the builder. This section walks you through exactly where to find and enable conditional logic so you can begin creating dynamic, personalized survey flows.

  
### **Step 1:** Open Your Survey Builder

1. Navigate to **Sites → Surveys** in your dashboard.
2. Create a new survey or edit an existing one.
3. Add at least one survey element (radio buttons, dropdown, etc.) to serve as a trigger.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048623415/original/pWVfb_MxgcqgQ9ef1k5LEfhYlgDOIb20MQ.gif?1750426429)
  
  
### **Step 2:** Open the Conditions Panel

1. In the survey builder toolbar, click the **middle icon** (conditional logic button). The Conditions panel will slide in from the right.
2. Alternatively, click the “Conditional Logic” link in the right sidebar.

> ⚠️ **Important**: If you cannot select any field in the “If” dropdown when building conditions, see the troubleshooting section below.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048623956/original/-42HFD2fu2qRGrvwY119Y0mhf8wTZkMojw.gif?1750426708)

---

## **Available Conditional Logic Options**

HighLevel surveys offer five powerful conditional logic types—Show/Hide Fields, Jump To, Display Custom Message, Redirect to URL, and Disqualify Lead, that let you tailor every respondent’s journey. Here are the five available conditional logic options:  

1. Show/Hide Fields
2. Jump To
3. Display Custom Message
4. Redirect to URL
5. Disqualify Lead

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048626723/original/RmSJ_Dqo0j7OAkCRRIa9cmE-vXbbGpa55w.jpeg?1750428402)
  
  
Whether you want to progressively reveal follow-up questions, branch users down different paths, surface context-aware messages, route qualified leads to custom pages, or automatically filter out unqualified prospects, there’s a rule type designed for the job.

  
| Option                     | When to Use                                                                                                                      | How to Set Up                                                                                                                                                                                                                                                                | Example                                                                                                                    |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Show/Hide Fields**       | \- Reveal follow-up questions only when relevant\- Hide sections for specific respondent types\- Build personalized survey paths | 1\. Choose **Show/Hide Fields**2\. **IF** block:\- Field: select trigger element\- Operator: Is Equal To, Contains, etc.\- Value: enter matching text\- (+) Add Condition to combine with And/Or3\. **THEN** block:\- Action: **Show** or **Hide**\- Target: select field(s) | IF “Service Interest” → “Is Equal To” → “Premium”THEN Show → “Premium Features Questions”                                  |
| **Jump To**                | \- Skip irrelevant slides for certain answers\- Create branching paths in your survey                                            | 1\. Choose **Jump To**2\. **IF** block:\- Field: select trigger element\- Operator: Is Equal To, Contains, etc.\- Value: enter matching option\- (+) Add Condition to combine with And/Or3\. **THEN** block:\- Target Slide: pick the destination slide                      | IF “Are you a new customer?” → “Is Equal To” → “No”THEN Jump To → “Existing Customer Questions”                            |
| **Display Custom Message** | \- Show personalized thank-you messages\- Provide conditional instructions or warnings                                           | 1\. Choose **Display Custom Message**2\. **IF** block:\- Field: select trigger element\- Operator: Is Equal To, Contains, etc.\- Value: enter matching criteria\- (+) Add Condition to combine with And/Or3\. **THEN** block:\- Message: Type your custom text in the editor | IF “Satisfaction Rating” → “Is Less Than” → “3”THEN Show Message → “We’re sorry to hear this—someone will reach out soon.” |
| **Redirect to URL**        | \- Send respondents to the landing pages by answers\- Route to product demos or custom pages                                     | 1\. Choose **Redirect to URL**2\. **IF** block:\- Field: select trigger element\- Operator: Is Equal To, Contains, etc.\- Value: enter matching option3\. **THEN** block:\- URL: paste full link (include https://)                                                          | IF “Budget Range” → “Is Equal To” → “Enterprise”THEN Redirect to → https://yoursite.com/enterprise-demo                    |
| **Disqualify Lead**        | \- Automatically filter out unqualified prospects\- Maintain CRM data quality                                                    | 1\. Choose **Disqualify Lead**2\. **IF** block:\- Field: select trigger element\- Operator: Is Equal To, Contains, etc.\- Value: enter matching criteria3\. The system marks the lead as **disqualified**                                                                    | IF “Annual Budget” → “Is Less Than” → “5000”THEN Lead is marked as **Disqualified**                                        |

---

## **Best Practices**

* Plan your logic flow before building and diagramming complex paths.
* Use clear, descriptive field names so rules are easy to manage.
* Keep rules simple where possible; nest “And/Or” sparingly.
* Test in **Preview** mode after each rule is added.
* Use progressive disclosure: reveal only what’s necessary to reduce survey length.

---

## **Troubleshooting: Fields Not Appearing in Conditional Logic?**

If you're unable to select any fields in the **IF** dropdown while setting up conditional logic, the likely cause is **missing or invalid Query Keys** on your survey fields.

### **What is a Query Key?**

The **Query Key** acts as an internal identifier for each field. If it's missing, duplicated, or left blank, the system cannot register that field in the logic builder, which causes it to be unselectable.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050585125/original/NOXrAjdwc3TDzx7pGJjQtaSBc4zN6yGemg.png?1753783794)

### **How to Fix It**

1. Go to your survey fields in the builder.
2. Make sure **every field has a unique and meaningful Query Key**.
3. Save the form.
4. Refresh the **Conditional Logic** panel.

Once you've done this, the fields should appear correctly in the dropdown for logic configuration.

---

## **Frequently Asked Questions**

  
**Q: Can I use Conditional Logic in existing surveys?**

No, Conditional Logic is only available for newly created or cloned surveys.

  
**Q: What field types are supported for Jump To Slide actions?**

Jump To Slide currently supports radio buttons and single-select dropdown fields.

**Q: What happens if two conditions overlap?**

Only the first valid condition (from top to bottom) will be executed.

**Q: Can I display a custom message when disqualifying a lead?**

Yes, you can set a custom message to show when a respondent is disqualified.

**Q: Is there a limit to the number of conditions I can add?**

No, you can add as many conditions as needed for your survey logic.

**Q: How do I reorder conditions?**

Use the drag-and-drop interface in the Conditions panel to change the order.

---

## **Related Articles**

  
* [Math Calculations in Forms/Surveys](https://help.gohighlevel.com/support/solutions/articles/155000003634-math-calculations-in-forms-surveys)
* [Survey Create Contact on Partial Completion](https://help.gohighlevel.com/support/solutions/articles/155000004191-survey-create-contact-on-partial-completion)
* [Workflow Trigger - Survey Submitted](https://help.gohighlevel.com/support/solutions/articles/155000003259-workflow-trigger-survey-submitted)[](https://help.gohighlevel.com/support/solutions/articles/48001224541-how-to-build-a-survey-in-gohighlevel)