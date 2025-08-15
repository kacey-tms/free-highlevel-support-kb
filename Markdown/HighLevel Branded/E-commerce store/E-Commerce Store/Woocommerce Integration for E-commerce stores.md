**Date Updated:** 2025-01-22T05:05:28.000Z
  
  
**TABLE OF CONTENTS**

* [About](#About%3A)
* [How to use](#How-to-use%3A)
* [Notes](#notes:)
* [Images](#Images%3A)
* [Triggers & Automations:](#Triggers-&-Automations%3A)  
   * [Order Submitted Trigger](#Order-Submitted-Trigger%3A)  
   * [Payment Received Trigger](#Payment-Received-Trigger%3A)

## About:

Store owners can now seamlessly import and sync their WooCommerce store data with HighLevel (GHL). This new feature allows store owners to easily migrate and manage their WooCommerce store by importing contacts, orders, and transactions into GHL. Additionally, WooCommerce store owners can leverage GHL’s marketing tools, including triggers like Order Submitted Trigger and Payment Received Trigger for better automation.

## How to use:

1. Access the Integration Settings:  
 Woocommerce integration can be found within a sub-account at:  
Settings > Integration > Woocommerce  
.
2. Connect the WooCommerce Store:  
Users can click on “connect” button to begin the setup. A modal will appear where users must enter a valid WooCommerce store URL (e.g.,  
https://yourstore.com  
 without a trailing slash) as the first step.
3. Select Data to Import:  
 In the second step, users will be directed to the Import Elements screen, where they can select which data to import from their WooCommerce store. The available options for import are: Contacts, Orders, Transactions.
4. Configure Syncing Settings:  
 The third and final step takes users to the Sync Settings screen, where users can choose which data to continuously sync from WooCommerce to GHL in future. The options for syncing include: Contacts, Orders, Transactions, Order submitted trigger, Payment received trigger.
5. Completing the Setup:  
After selecting the desired elements to import and sync, click Save. The import and sync process may take some time to complete.
6. Manage Settings:  
 Once the WooCommerce integration is successfully connected, users can enable or disable the elements they want to sync for future orders from the WooCommerce store.
7. Reimporting Data:  
 If users wish to reimport data, they can disconnect and reconnect the integration, allowing them to reimport any data they may have missed during the initial import.

## Notes:

1. Woocommerce Integration Criteria:  
 Sub-accounts within the same agency can connect to the same domain. However, an agency can only be linked to one WooCommerce account. If the WooCommerce account is already connected to another agency, the current agency will not be allowed to connect.
2. Customer Type Import:  
 Customers with role “customers” & “subscribers” will be imported.
3. Contact Creation with Disabled Customer Sync:  
Even if Contact sync is disabled and the Order sync is enabled, contacts will be created related to the order.
4. Guest Checkout Handling:  
Guest checkout customers will be created as contacts, but no updates or future syncs will occur for these guest accounts.
5. WooCommerce Status Mappings:  
 The following mappings will apply for syncing order statuses from WooCommerce to GHL:  
   1. **Completed** or **Refunded** in WooCommerce → **Completed** in GHL  
   2. **Cancelled** or **Failed** in WooCommerce → **Cancelled** in GHL  
   3. All other statuses in WooCommerce → **Pending** in GHL

## Images:

* Woocommerce Integration:
* Woocommerce link:
* Import Elements:

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039795299/original/53iTALmyfo-SNOc7ejmfxT46_56eYUvpUg.jpeg?1736853408)

* Approve Woocommerce permissions:
* Modify sync options in Settings:
* Orders page has Subtype of Woocommerce:

## **Triggers & Automations:**

1. ### **Order Submitted Trigger:**  
Order Submitted trigger can be setup for Woocommerce Orders in GHL by searching "Order Submitted" trigger in workflow trigger list:  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039794908/original/hCiZFuVk108vsePN4LnBoLOVMVQs502dYg.png?1736853148)  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039790277/original/B19QDVLHxsuED1VIi9RHh767uhYz_OPQ3Q.png?1736850197)  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039790362/original/THMQ5QyLgNppx7hwllkozMytCCWcUrc7uA.png?1736850239)
2. ### **Payment Received Trigger:**  
Payment Received trigger can be setup for Woocommerce Orders in GHL by searching "Payment Received" trigger in workflow trigger list:  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039795203/original/gE9Rr1hgh9X_JS4Xx_2pGcnqNW0tV233cg.png?1736853356)  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039795264/original/bz4cbYHhf8ixyjaKlklajzSGvhHvaNifMQ.png?1736853384)

  