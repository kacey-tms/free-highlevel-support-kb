**Date Updated:** 2025-06-30T19:01:04.000Z

Easily pass processing charges, convenience fees, or other additional fees to your customers with HighLevel’s new Processing Charge feature. This guide explains how to set up, customize, and manage additional fees for payments, helping you recover costs and maintain transparency at checkout.

  
**IMPORTANT**: **Compliance Note** - It is your responsibility to comply with applicable laws concerning surcharging, as it may be prohibited in certain jurisdictions.

---

**TABLE OF CONTENTS**

* [What is the Processing Charge Feature in HighLevel?](#What-is-the-Processing-Charge-Feature-in-HighLevel?)
* [Important Behavior Guidelines](#Important-Behavior-Guidelines)
* [How to Configure a Processing Charge](#How-to-Configure-a-Processing-Charge)  
   * [Step 1: Access Payment Settings](#Step-1%3A-Access-Payment-Settings)  
   * [Step 2: Define the Processing Charge](#Step-2%3A-Define-the-Processing-Charge)  
   * [Step 3: Select Payment Sources to Apply the Charge](#Step-3%3A-Select-Payment-Sources-to-Apply-the-Charge)
* [Viewing Processing Charges in Checkouts](#Viewing-Processing-Charges-in-Checkouts)
* [Viewing Processing Charges in Reports](#Viewing-Processing-Charges-in-Reports)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

---

## **What is the Processing Charge Feature in HighLevel?**

  
The Processing Charge feature in HighLevel allows businesses to automatically add extra fees, such as processing charges, convenience fees, or miscellaneous charges to customer payments. This functionality is designed to help businesses offset costs associated with payment processing and provide clear, itemized fees to customers during checkout or invoicing.

  
**A Processing Charge** is an additional fee applied to a customer’s transaction total to cover costs such as payment processing or miscellaneous service fees. This charge is visible to customers at checkout and reflected on their payment receipt.

The processing charge is applied to the amount calculated as:  
**(Subtotal - Discounts + Taxes)** — which represents the actual amount processed through the payment provider.

  
By enabling this feature, you can define the percentage of the fee, customize how it appears to customers, and choose which payment channels (Invoices, Funnels, Payment Links, Forms, Surveys) the fee applies to. The fee is calculated based on the actual transaction amount, ensuring accuracy and transparency.

  
### **Where Does This Fee Apply?**

  
Processing charges can be applied to the following payment sources:

  
1. Invoices
2. Funnels
3. Forms
4. Surveys
5. Payment Links
6. Estimates

  
**IMPORTANT**: While all payment providers are supported on Invoices & Estimates, other checkouts don't support this feature on PayPal and Custom Payment Providers.

---

## **Important Behavior Guidelines**

  
* Draft invoices reflect the processing charge only if edited after the feature is enabled.
* Invoices already sent or orders already placed before enabling this feature remain unaffected.
* Disabling the feature does not retroactively remove charges from existing invoices or orders unless those documents are still editable.
* Processing charges are displayed as a distinct line item during checkout and included in the final total shown to the customer.
* This charge will not apply to Invoices paid via the mobile app, that feature is Coming Soon.

---

## **How to Configure a Processing Charge**

  
Setting up processing charges ensures you can efficiently manage additional fees and provide clear information to your customers. Follow these steps for a smooth setup:

  
### **Step 1:** Access Payment Settings

  
1. Go to the platform dashboard.
2. Navigate to **Payments > Settings**.
3. Scroll down to the **Miscellaneous Charges** section.
4. Within this page, select the section for **Processing Charges**.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048999917/original/lCASgu57QWlKOhd7HwqOYYGs5GlfQDPyLg.gif?1751035783)
  
  
### **Step 2:** Define the Processing Charge

  
1. Enable the **Processing Charges** toggle.
2. Enter the **fee percentage** to be applied (e.g., 2.5%).
3. Define a **custom label/name** for the fee (e.g., Convenience Fee, Processing Charge, etc.). This label/name will appear on the customer’s checkout summary and receipt.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049000212/original/fJEgVNTwGUlubdvlhyRc0sD2R1QJGCFIVw.gif?1751036024)
  
  
### **Step 3:** Select Payment Sources to Apply the Charge

Use the available checkboxes to choose where the processing charge should apply:

* Invoices
* Funnels
* Payment Links
* Forms
* Surveys
* Estimates

  
Select one or multiple options as needed.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049000261/original/n_7v_TDFCwChCMS4MEzC61a4uFQRvFTjsg.png?1751036076)

  
**Note**: Click **Save** to confirm the configuration. The processing charge will be applied automatically on the selected payment sources at checkout.

---

## **Viewing Processing Charges in Checkouts**

  
1\. **Invoices & Estimates** \- The processing charges are shown after the 'Pay' button is clicked for an Invoice. 

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048208440/original/_HkFa2jLE1xGoNTcBmw63VgImMeqRPBw4g.png?1749811467)
  
  
2\. **Funnels, Forms, Payment Links** \- The charge is shown as part of the total amount.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048208610/original/_P6RsSakZw7v5LqBgW1CFKATnOrJuMJCEg.png?1749811556)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048208656/original/oB7yMm7xV-tBZ-Cgw-I5i56jceSsq9S2ww.png?1749811604)

---

## **Viewing Processing Charges in Reports**

  
Get a clear, itemized breakdown of every processing fee you’ve applied, filter by date range, payment channel, or custom label, and export the results for easy reconciliation and analysis. To track applied processing charges.

  
* Open the **Transactions CSV** or **Orders CSV** export.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049088906/original/fvcJlbxyjXGTZdZRjuUKMIPzsgvlXyifwQ.png?1751289701)

  
These fields provide details of any processing charges applied to individual transactions and orders.

---

## **Frequently Asked Questions**

  
**Q: Can I set different processing charges for different payment channels?**

Not yet. Currently, the same fee applies across all selected channels, but channel-specific fees are planned for future updates.

**Q: Will disabling the processing charge remove it from past invoices?**

No, disabling the feature only affects new invoices or orders. Existing records retain the fee unless they are editable.

**Q: Are processing charges supported for all payment providers?**

All providers are supported for Invoices & Estimates, but PayPal and Custom Payment Providers are not supported for other checkouts.

**Q: How is the processing fee calculated?**

The fee is calculated on (Subtotal - Discounts + Taxes), representing the actual transacted amount.

**Q: Can I apply processing charges to mobile app payments?**

Not currently. This functionality is coming soon.

**Q: Where do customers see the processing charge?**

Customers see the fee as a separate line item during checkout, on invoices, and on transaction receipts.

**Q: Can I customize the name of the processing charge?**

Yes, you can set a custom label that will be displayed to customers.

**Q: Is there reporting for processing charges?**

Yes, transaction and order exports include the fee label and amount.

---

## **Related Articles**

* [Rebilling, Reselling, and Wallets Explained](https://help.gohighlevel.com/support/solutions/articles/155000002095-rebilling-reselling-and-wallets-explained)
* [ACH Debit payment method on invoices](https://help.gohighlevel.com/support/solutions/articles/155000000611-ach-debit-payment-method-on-invoices)
* [Tap to Pay on Square for POS and Mobile Payments](https://help.gohighlevel.com/support/solutions/articles/155000005506-tap-to-pay-on-square-for-pos-and-mobile-payments)