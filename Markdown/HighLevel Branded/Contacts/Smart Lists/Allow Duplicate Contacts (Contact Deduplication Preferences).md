**Date Updated:** 2025-07-23T19:46:36.000Z

The **"Allow Duplicate Contact"** setting controls how duplicate contacts are managed in HighLevel. This setting is particularly relevant for contacts submitted through **Zapier** or **Forms**. However, it does not apply to **CSV contact uploads**, where duplicates are automatically identified and managed based on phone numbers or email addresses. This guide explains the setting's behavior, configuration, and key details.

---

**TABLE OF CONTENTS**

* [Key Details Before Allowing Duplicates](#Key-Details-Before-Allowing-Duplicates)
* [How to Configure the "Allow Duplicate Contact" Setting](#How-to-Configure-the-)
* [Behavior Across Contact Sources](#Behavior-Across-Contact-Sources)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

---

## **Key Details Before Allowing Duplicates**

  
1. **Applies to Zapier and Forms:**  
   * The **"Allow Duplicate Contact"** setting only applies to contacts coming through **Zapier** or **Forms**.  
   * When enabled, duplicate records with the same phone number or email can be created.  
   * When disabled, new submissions with duplicate information update existing contacts instead of creating new ones.
2. **Does Not Apply to CSV Imports:**  
   * For CSV imports, GoHighLevel automatically merges contacts based on **phone numbers** or **email addresses**, regardless of the setting.  
   * Duplicate contacts cannot be created via CSV uploads.
3. **Default Behavior for Imports:**  
   * When importing contacts via CSV, the system checks for existing records using the specified **primary field** (email or phone).  
   * Contacts with matching information are merged automatically, ensuring a clean and organized database.

  
When **enabled** this setting, "Allow Duplicate Contacts", duplicate contacts are allowed, which can be useful in workflows where the same individual needs to exist as separate records (e.g., different departments).  
When **disabled**, duplicate contacts are prevented, ensuring a single record per phone or email and updates are made to existing records instead of creating new ones.

---

## **How to Configure the "Allow Duplicate Contact" Setting**

  
This setting is located under Settings → Business Profile → Contact Deduplication Preferences and offers additional customization options, such as setting primary and secondary criteria for duplicate detection.

  
**Step 1**: Go to **Settings** from the left-hand menu of the Subaccount/Location.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040612864/original/1UU-k4RexJN00Bxvpwk-nVlJva5z0zFiQQ.png?1738106670)
  
  
**Step 2**: Click on **Business Profile** and under the **My Business** section, locate the **Contact Deduplication Preferences** panel on the right-hand side of the screen.

  
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155040612911/original/p9xvdNia1IYqmsbMrv3inMqwV1AJiqomXw.png?1738106845)**  

  
### **The "Find Existing Contacts based on" Filter:** 

  
This filter allows you to specify how HighLevel identifies and matches existing contacts in your database. You can select one or both of the following fields:  
  
1. **Primary Field:**  
   * Choose the main field to check for duplicates:  
         * **Email** (default): Matches contacts based on email addresses.  
         * **Phone**: Matches contacts based on phone numbers.
2. **Second Preference for Search (Optional):**  
   * Use this field as a secondary criterion for duplicate detection.  
   * Example: If "Email" is selected as the primary field and "Phone" as the secondary, the system will first match by email and, if no match is found, check by phone number.

---

## **Behavior Across Contact Sources**

  
1. **Forms and Zapier:**  
   * **Enabled:** Allows duplicates, creating separate records for contacts with the same email or phone.  
   * **Disabled:** Updates the existing contact with the new information instead of creating a duplicate.
2. **CSV Imports:**  
   * Duplicate records are merged automatically based on phone number or email.  
   * Duplicate contacts cannot be created during CSV imports, regardless of the setting.

  
If you wish to learn more on Importing Contacts, please refer to the following article- [Importing Contacts and Opportunities via CSV](https://help.gohighlevel.com/support/solutions/articles/155000003905-importing-contacts-and-opportunities-via-csv)

---

## **Frequently Asked Questions**

  
**Q: Can duplicates be created during CSV imports?**

No, duplicate contacts cannot be created during CSV imports. The system automatically merges contacts based on email or phone.

  
**Q: What happens if I enable "Allow Duplicate Contact"?**

Contacts with the same phone number or email can be created via Forms or Zapier. Duplicate contacts cannot be created via CSV uploads.

  
**Q: Can I merge duplicate contacts after enabling this setting?**

Yes, duplicate contacts can be manually merged using the **Merge Contacts** feature.

  
**Q: How can I prevent duplicates from integrations?**

Disable the **"Allow Duplicate Contact"** setting in your account settings to ensure integrations update existing records instead of creating new ones.

---

## **Related Articles**

* Merging Multiple Contacts
* Bulk Importing Contacts via CSV Walkthrough