**Date Updated:** 2025-02-10T10:17:11.000Z

The Stripe One-Time Charge workflow action in HighLevel allows businesses to automate payments by charging customers per lead, appointment, or form submission eliminating manual invoicing and streamlining the payment process. This guide will walk you through what this feature is, its key benefits, prerequisites, and step-by-step instructions on how to configure it.
  
  
---

**TABLE OF CONTENTS**

* [What is Stripe One-Time Charge Workflow Action](#What-is-Stripe-One-Time-Charge-Workflow-Action)
* [Key Benefits of Stripe One-Time Charge Action](#Key-Benefits-of-Stripe-One-Time-Charge-Action)
* [Integrating Your Stripe Account with HighLevel](#Integrating-Your-Stripe-Account-with-HighLevel)
* [Configuring Stripe One-Time Charge Action in HighLevel](#Configuring-Stripe-One-Time-Charge-Action-in-HighLevel)  
   * [Setting Up the Workflow Trigger](#Setting-Up-the-Workflow-Trigger)  
   * [Add Stripe One-Time Charge Action](#Add-Stripe-One-Time-Charge-Action)  
   * [Enter Customer ID](#Enter-Customer-ID)  
   * [Description](#Description)  
   * [Amount](#Amount)  
   * [Currency](#Currency)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What is Stripe One-Time Charge Workflow Action**

  
The Stripe One-Time Charge action is a workflow automation feature that enables businesses to charge a predefined amount each time a specific event occurs. This could be a form submission, an appointment booking, or any other predefined trigger. When an event happens, the workflow automatically processes the payment using the customer’s Stripe ID, ensuring seamless transactions without manual intervention.

  
For example, an agency using a pay-per-lead model can automatically charge clients each time a qualified lead fills out a form, ensuring instant payments without chasing invoices.

---

## **Key Benefits of Stripe One-Time Charge Action**

  
Below are some of the key advantages of using this feature in your workflows:

  
* **Automated Billing:** Eliminates the need for manual invoicing by automatically charging customers based on workflow triggers.

  
* **Seamless Integration:** Works with Stripe, ensuring a secure and reliable payment process.

  
* **Customizable Triggers:** Allows businesses to charge customers based on specific conditions like appointment confirmations or form submissions.

---

## **Before Integrating Your Stripe Account with HighLevel**

  
Before using the Stripe One-Time Charge action, your Stripe account must be integrated with HighLevel. Here is how you can do it:

1. Go to **Settings** area in your HighLevel Sub-account location where you want to use stripe one time charge automation.
2. Click on the **Integrations** Tab.
3. Select Connect to Your Stripe Account.
4. Log in to Stripe and grant access to HighLevel.
5. Once connected, your HighLevel account will be linked to Stripe, enabling payment processing.

---

## **Configuring Stripe One-Time Charge Action in HighLevel**

  
Once Stripe is integrated and you have the necessary Customer ID, follow these steps to configure the Stripe One-Time Charge workflow action:

  
### **Create or Open a Workflow**

  
Navigate to **Automation** in HighLevel. Select Workflows and either create a new workflow or open an existing one.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040882420/original/BnEH3nUsbAZFpcXLXGMkSn6afNHShGM_GA.png?1738569039)
  
  
### **Setting Up the Workflow Trigger**

  
Click **Add New Trigger**. Scroll down to view all available triggers and select an appropriate trigger for your workflow (e.g., Form Submission or Appointment Booking). Apply filters such as specific forms, appointment calendars, or confirmation statuses.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040882453/original/oewXBKr-qM8eY-G8-2i184vjhCGMWgTaHg.png?1738569069)
  
  
### **Add Stripe One-Time Charge Action**

  
Click the **+** icon to add an action. Search for **Stripe One-Time Charge** and select it.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040882471/original/yEcVDqjyWJMNU0ZbVWP5Jsiu9gKbgYtarg.png?1738569092)
  
  
### **Renaming the Action**

  
By default, the action is named “Stripe One-Time Charge”, but you can rename it for better clarity and organization. Giving it a descriptive name makes it easier to understand the action’s purpose at a glance.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040882546/original/xy7HyiwE0J_klKO4PapMOIZVMtLNjs830Q.png?1738569141)
  
  
### **Enter Customer ID**

  
To charge a customer through Stripe, you need their Stripe Customer ID. This is a unique identifier assigned to each customer within Stripe. Without this ID, the workflow cannot process the charge. Copy the code (Customer ID) from your stripe dashboard and paste it into the Customer ID field. 

  
**To find the Stripe Customer ID:**

  
1. Log in to your Stripe account.
2. Navigate to the **Customers** tab.
3. Click on the specific customer.
4. Under **Details**, locate the **Customer ID** and copy it.

  
If the customer has never made a payment through Stripe, they might not have a Customer ID yet. In such cases, you may need to create a customer in Stripe manually.

  
**To Create a Customer Manually:**

  
Go to Stripe Dashboard → Customers Tab → Click “+ Add Customer”.

Once created, Stripe will generate a Customer ID, which can be used for future charges.
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040882605/original/nbYrQSL9BSC3L7uUYVB4mUl5kqVocvdvbg.png?1738569171)
  
  
### **Description**

  
Adding a description helps in keeping records organized by providing context about the transaction. You can enter details such as the purpose of the charge (e.g., “Lead Fee for Appointment Booking”). This description will also appear in Stripe, making it easier to track payments and reconcile transactions later.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040882663/original/NhgztZ12aQ1tbMjaTSW3sRNtpKnI9sFgww.png?1738569220)
  
  
### **Amount**

  
Enter the charge amount in this field. If the amount varies, use the tag icon next to it to select a dynamic value from the Custom Variable Picker, ensuring automated and accurate billing.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040882689/original/3VWeqz9y1yjzVcKe327RGVb4DIyUtdGouA.png?1738569251)
  
  
### **Currency**

  
Select the preferred currency for the charge using the dropdown menu. This ensures the transaction is processed in the correct currency based on your business or client’s location.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040882719/original/0QyPdSX_9I-QSGHscDJajADlZ5E11V2Jxg.png?1738569281)
  
  
**Save and Publish**  
  
- Click **Save** button to apply the changes made in the workflow builder.  
  
- Enable the **Publish** toggle to activate the workflow.  
  
  
**Testing the Workflow**  
  
- Book an appointment or submit a form that triggers the workflow.  
  
- Check **Enrollment History** tab within the workflow builder to verify if the charge was processed.  
  
- Log into Stripe to confirm the payment transaction.

  
---

## **Frequently Asked Questions**

  
**Q. Can I charge customers without a Stripe Customer ID?**

No, a Stripe Customer ID is required for processing payments through the workflow.
  
  
**Q. What happens if the payment fails?**

If the charge fails, Stripe will display an error in the transaction history, and no payment will be processed.
  
  
**Q. Can I issue a refund if needed?**

Yes, refunds can be processed directly within Stripe by navigating to the Payments tab and selecting the transaction.
  
  
**Q. Can I charge different amounts for different triggers?**

Yes, you can create multiple workflows with different charge amounts based on different triggers.
  
  
**Q. Does this work for subscription payments?**

No, this action is for one-time charges only. For subscriptions, use Stripe’s recurring billing options.