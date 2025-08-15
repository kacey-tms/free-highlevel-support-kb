**Date Updated:** 2025-06-27T17:30:40.000Z

Custom Objects feature is available only on the $497 plan

This document provides a comprehensive overview of the "Association for Custom Objects" feature, detailing how users can establish associations between custom objects and contacts or between custom objects themselves. 

  
**In This Article**

  
   * [Creating Associations](https://help.gohighlevel.com/a/solutions/articles/155000003063?portalId=48000045315#Creating-Associations)
   * [Managing Associations](https://help.gohighlevel.com/a/solutions/articles/155000003063?portalId=48000045315#Managing-Associations)
   * [Associating Two Records Using One or Multiple Labels](https://help.gohighlevel.com/a/solutions/articles/155000003063?portalId=48000045315#Associating-Two-Records-Using-One-or-Multiple-Labels)

[](https://help.gohighlevel.com/a/solutions/articles/155000003063?portalId=48000045315#Feature/action-1---Filtering)

---

## Creating Associations

#### Steps to Create Associations:

1. **Access the Custom Objects Section:**  
   * Navigate to **Subaccounts > Settings > Custom Objects**.  
   * Select the custom object you wish to create an association for.  
   * Click on the **Associations** tab.![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155035119353/original/tHWcvLbNOAHyiSGT_cv8qrMYhRkN1Ovm7Q.jpeg?1729526289)
2. **Set Up Labels:**  
   * You can choose to set a single label or a pair of labels to define the relationship.  
   * Example: For associating a car with its owner, you might set the labels as “Owner” and “Car."  
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155035119351/original/3pwtkLx6AdElN5WSpOXbJ_SVrOLNsiR_yg.jpeg?1729526287)

All current associations are many-to-many in nature. 

1. **Save and Apply:**
* After naming and setting up the association labels, click **Save**.
* You can now use these labels to associate records in your custom objects or between a custom object and a contact.

  
You can create upto 10 association labels between two contacts or between a contact-to-custom object combination
  
  
## Managing Associations

1. **View Associations:**  
   * Go to the record details of the custom object.  
   * On the right side panel, you will find the associations listed under the **Related Objects** section.  
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155035119358/original/4CMAdAr9XnSKo9qQy6ebskFeT2s6ND4v0g.jpeg?1729526290)
2. **Editing Associations:**  
   * If needed, you can remove an association by selecting the association label, clicking on the kebab menu (3 dots icon) and selecting Edit  
   * The label name can be updated but not the internal name for the same.![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155035119354/original/7ivo9nP6_HW5VtXfsSylgw1jQb4cnYWNfA.jpeg?1729526290)
3. **Removing Associations:**  
   * If needed, you can remove an association by selecting the association label, clicking on the kebab menu (3 dots icon) and selecting delete  
   * Type "DELETE" in the text box and then click the **delete** button.  
   * Note that the delete action can only be performed if there are no existing relations between two different records using the mentioned label.![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155035119350/original/RSIZ5GAmA2buelauGr6fVXQA_mcnbPFA4A.png?1729526287)

  
## Associating Two Records Using One or Multiple Labels

  
1. **Access the Records:**  
   * Navigate to the **Custom Objects** section or **Contacts** where your records are stored.  
   * Open the detail view of one of the records you wish to associate.
2. **Initiate the Association Process:**  
   * On the right-hand side panel, locate the **Related Objects** section.  
   * Click on the **Association** icon (often represented as a link or chain icon) to begin setting up the association.![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155035119355/original/deYTkTYc_a4xu7ZOWa3rlnfSW6uJRlfvuQ.jpeg?1729526289)
3. **Select the Object to Associate With:**  
   * In the association setup window, choose the object you want to associate with the current record. This can be another custom object or a contact.  
   * Select the labels you want to associate the two objects with  
   * Confirm the setup by clicking **Save**.![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155035119352/original/geJQMGdfj8rGpvI8aj3OI9CGt06AhxccaA.jpeg?1729526289)
4. **Finalizing the Association:**  
   * The association will now appear under the **Related Objects** section of the record’s details.  
   * You can click on the associated object or contact to view the relationship and modify or delete it as needed.
5. You can also add the associated objects as columns in the list view for quickly accessing which records is any object record associated with.

Each label can associate a maximum of 1000 records

  
Learn more about contact to contact associations [here](https://help.leadconnectorhq.com/en/support/solutions/articles/155000003919-associating-contacts-using-custom-labels-coming-soon-). 

---

## **Frequently Asked Questions**

  
**Q: Can I automatically associate a Contact with a Custom Object if they share the same field value (like Email)?**

No, automatic associations based on matching field values (such as Email) are not currently supported in HighLevel. Associations must be created manually through the interface using the Related Objects panel or programmatically via API. If you need automated linking based on field values, consider using a custom integration or submitting a feature request.

  
**Q: How many associations can I create between records?**

You can create up to **10 unique association labels** between any two records—whether it’s Contact-to-Contact, Contact-to-Custom Object, or Custom Object-to-Custom Object. Each label can be used to associate a maximum of **1,000 records**.

  
**Q: Can I edit or rename an association label after creating it?**

You can update the **label name** used for associations through the Association tab settings, but the **internal name** remains fixed once the label is created. If you need to change the internal reference, you’ll need to delete the original label (only if no active relationships exist) and create a new one.