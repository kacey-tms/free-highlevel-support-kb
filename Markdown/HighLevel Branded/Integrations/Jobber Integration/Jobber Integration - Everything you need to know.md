**Date Updated:** 2025-08-06T07:43:12.000Z

**TABLE OF CONTENTS**

* [Can I connect more than one sub-account to a single Jobber account?](#Can-I-connect-more-than-one-sub-account-to-a-single-Jobber-account?)
* [How long does it take for the initial contacts<>clients sync between HighLevel and Jobber?](#How-long-does-it-take-for-the-initial-contacts%3C%3Eclients-sync-between-HighLevel-and-Jobber?)
* [What all fields are synced between HighLevel and Jobber?](#What-all-fields-are-synced-between-HighLevel-and-Jobber?)
* [What details are not synced between HighLevel and Jobber?](#What-details-are-not-synced-between-HighLevel-and-Jobber?)
* [How does HighLevel match clients with Contacts?](#How-does-HighLevel-match-clients-with-Contacts?)
* [Can I pause or stop the 2-way sync?](#Can-I-pause-or-stop-the-2-way-sync?)

  
# **Getting Started**

### **As an Agency admin, how do I get started with setting up the Jobber Integration?**

* The Jobber integration is provided as an app listed on the HighLevel App Marketplace.
* The app can only be viewed and installed by agency admins, as the app includes a snapshot that packages workflows, email and message templates, etc. that fast-track the setup of the integration for your clients.
* The app is not visible/available to sub-accounts until the agency has install the app.
* At the time of installation, you can bulk install the app to multiple-sub-accounts.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050867292/original/pNJMOkWeOz2OwE3qSH9PwUGZGayevEmgjQ.png?1754296545)

  
### **I installed the app to my client(s). What next?**

* Your clients can find the integration under 'Installed Apps' page in App Marketplace.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050868243/original/NEQUIlt7sin1mo0cVKtNiZXOqF_s9lM7aw.png?1754297132)

  
* Once they click on it, it'll take them to 'External Connection' page where they can connect with Jobber.

#   

# **FAQs**

### **Can I connect more than one sub-account to a single Jobber account?**

No, Jobber only supports one active connection. This means that you can only connect one HighLevel sub-account to a unique Jobber account.

  
### **How long does it take for the initial contacts<>clients sync between HighLevel and Jobber?**

Jobber allows syncing about 2500 records for every 5 minutes. So based on the start date you're selecting in "Sync Data" tab in your Jobber app, the system will take the necessary time to sync all the clients data inside HighLevel.

  
### **What all fields are synced between HighLevel and Jobber?**

* First Name
* Last Name
* Email
* Phone Number
* Address
* Lead Source
* Jobber Client URL (Custom field on HighLevel)
* Jobber Created Date (Date when the client was created on Jobber)
* **Tags**

  
### **What details are not synced between HighLevel and Jobber?**

* Custom Fields on Jobber
* Notes
* Attachments

  
### **How does HighLevel match clients with Contacts?**

HighLevel maintains the Jobber client's unique ID. This allows to maintain the sync even if you update the email or phone number 

  
### **Can I pause or stop the 2-way sync?**

No, we currently don't have that option. To stop the sync without disrupting your workflows build in Jobber, you must disconnect the app from Jobber by navigating to **Jobber App Marketplace > Connected Apps > LeadConnector App** and click the **Disconnect** button.

### **Once I've initiated the sync, can I go back and change the start date for syncing my historic client data?**

No, syncing historic data from Jobber is allowed only once while initiating the Jobber data-sync. Once we've synced the historic data, you cannot modify the timelines and reinitiate the sync from a different start date.

However, all new clients-related data generated going forward will be synced live between the two platforms.

  
### **Can I view logs of clients data that was synced?** 

The sync-logs are currently not available. 