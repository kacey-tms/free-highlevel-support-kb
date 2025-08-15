**Date Updated:** 2025-05-16T17:42:22.000Z

### **Overview**

This document outlines the steps to resolve an issue where duplicate contacts are created for WhatsApp messages, even when the "Allow Duplicate Contact" setting is disabled in the Business Profile.

### **Symptoms**

* Duplicate contact entries are displayed for WhatsApp messages.
* The **Allow Duplicate Contact** option is disabled under **Business Profile** settings.
* Despite this, the duplication persists.

### **Cause**

This issue may occur if the contact search preferences are not configured to include phone numbers as a secondary search criterion.

### **Resolution Steps**

1. Navigate to **Business Profile**.
2. Go to **Contact Duplicate Preference**.
3. Under **Second Preference for Search (Optional)**, ensure that **Phone** is selected.

### **Explanation**

Selecting **Phone** as the secondary preference for contact search enables the system to match contacts based on phone numbers, which helps prevent the creation of duplicate contact entries.
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046756067/original/zQIwXKjIu8u1YlZnPiixEeGlN56VvGhRVA.png?1747396808)