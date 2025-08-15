**Date Updated:** 2025-07-09T16:24:12.000Z

**1. Agencies on** **Any Plan**($97, $970, $297, $2970, $497, $4970) can access Auto complete address.  
**2.** For agencies to avoid accruing execution costs for EXISTING Sub-Accounts, rebilling will need to be enabled **manually** for each Sub-Account within the Agency view.  
**3.** If Autocompleted Address is **enabled** on the SaaS Configurator, new Sub-Accounts generated will automatically be enrolled in Auto complete Purchase, **no further** action is required by the agency.

  
**TABLE OF CONTENTS**

* [1\. Enabling Auto-Complete in Forms/Surveys](#1.-Enabling-Auto-Complete-in-Forms/Surveys)
* [2\. Mandatory Address Selection (Search Bar)](#2.-Mandatory-Address-Selection-%28Search-Bar%29)
* [3\. Form-Level vs Agency-Level Control](#3.-Form-Level-vs-Agency-Level-Control)  
   * [Form-Level Control](#Form-Level-Control)  
   * [Agency-Level Control](#Agency-Level-Control)
* [4\. Auto Complete Address Purchase Pricing](#4.-Auto-Complete-Address-Purchase-Pricing)
* [5\. Re-Billing Clients (497 SaaS Mode Agencies Only)](#5.-Re-Billing-Clients-%28497-SaaS-Mode-Agencies-Only%29)
* [6\. How does re-billing work?](#6.-How-does-re-billing-work?)

---

## 1\. Enabling Auto-Complete in Forms/Surveys

For any form or survey where you want the address search bar:

**Steps:**

1. Go to **Sites > Forms** (or **Surveys**).
2. Open the builder.
3. Drag and drop the updated **Address** element onto your form.
4. Select the Address element and enable the **Auto-Complete Address** toggle.
5. The form will now show an **address search bar**.
6. Users can type and select an address from suggestions. The system automatically fills in:  
   * Street  
   * City  
   * State  
   * Country  
   * Postal/Zip Code

## ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042540267/original/xF5ZcC0ljpSK5bHJ0orh82WPvrKtFPbluw.png?1741005745)

## ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042540334/original/nBuuTsjdng23kb4iZC9YTZEA-Qh9qfTmvg.png?1741005782)
  
  
## ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042540303/original/ucBRdwukG8oMWZ_2Tt9yy2etICQWocS80A.png?1741005765)

## 2\. Mandatory Address Selection (Search Bar)

You can make selecting an address **mandatory**, ensuring users must choose a valid address from search suggestions.

**What This Toggle Does:**

* **Enabled:** Users must pick a valid address from the search results to proceed.
* **Disabled:** Users can submit the form without using the search bar.

**Use Case:**

* For simpler forms, you can hide other address fields entirely. Users only see the search bar, but the submission still includes the complete address.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155042540190/original/lPkQMBXUUIu_wMV7BCpHr_J7RQxZmoStAA.png?1741005694)

  
## 3\. Form-Level vs Agency-Level Control

There are two levels of control for the Auto-Complete Address feature:

### **Form-Level Control**

* Set individually for each form or survey.
* Turn **on** to show the **address search bar**.
* Turn **off** to hide the search bar entirely (manual entry only).
* Only affects that specific form.

### **Agency-Level Control**

* Controlled in **Agency Settings > Auto-Complete Address Purchase**.
* Acts as a master switch for the entire location.
* If **disabled** at the agency level:  
   * No forms in that location can use the search feature.  
   * Users can still manually enter address fields, but no search results will appear.  
   * Form-level toggles have no effect when globally disabled.

**Important:** Agency-level settings override form-level settings. You can access Sub-Account Settings only if **Autocomplete Address Purchase** is enabled at the Agency Level.![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155034822701/original/rWXVwzkYaIRbmxi6JasTRI-MjibpqHvUJA.png?1729088484)
  
  
**Please Note:**

**Agencies on Any Plan  ($97, $970, $297, $2970, $497, $4970) can access Autocomplete Address.**

##   

## 4\. Auto Complete Address Purchase Pricing

* Once Auto complete is enabled, you can drag and drop new address element and turn on autocomplete inside forms and surveys.
* If autocomplete toggle is on, it is chargeable at the cost of 0.002972 for search request made to google address API and 0.00525 per API call for filling details on address selection.

##   

## 5\. Re-Billing Clients (497 SaaS Mode Agencies Only)

Agencies on the 497 SaaS plan can resell the Auto-Complete Address feature to their sub-accounts and add their own markup.

**How to Enable Re-Billing:**

1. Enable Auto-Complete Address Purchase at the **Agency level** (see above).
2. Make sure the sub-account is in **SaaS Mode**:  
   * Go to **Agency > Accounts**.  
   * Find the sub-account, click the **three dots**, and select **Switch to SaaS**. [Link to Saas Mode Set Up and Guide](https://help.gohighlevel.com/support/solutions/articles/48001184920).
3. In **Agency > Accounts**, click **View Details** for the sub-account.
4. Scroll to **Auto-Complete Address Purchase Re-Sell Settings**.
5. Toggle it **on**.
6. Use the slider to set your markup amount.
7. Save your changes.

Repeat these steps for each sub-account you want to re-bill.

##   

## 6\. How does re-billing work?

* Agencies pay HighLevel and get invoices with high-level branding
* Sub-accounts (your clients) pay you (the agency) and get invoices with your branding. The money is deposited in your Stripe account connected to your agency level. [How do I connect my agency's Stripe account to collect client payments?](https://help.gohighlevel.com/en/support/solutions/articles/48001171910)

  
This is very similar to other products that use re-billing or reselling models in the platform. Just like LC Phone or LC Email re-billing, re-billing of the Auto Complete Address also utilises "credits" from the agency wallet & the location wallet, respectively. 

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155034243061/original/DdGcs2fY8rMznF6O0HeeFNJSLke6htd6Kw.jpeg?1728311495)

  