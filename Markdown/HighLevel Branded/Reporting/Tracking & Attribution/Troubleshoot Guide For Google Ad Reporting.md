**Date Updated:** 2022-09-05T19:34:16.000Z

Google AdWords is one of the most popular advertising platforms in the world. It’s a great way to promote your business and get more traffic, but it can be difficult to track how well you are doing with this platform. 

  
If you want to know what is going on with your ads, then you need to use Google AdWords reporting. In this guide, we will show you a few troubleshooting steps to see if your Google Ad Setup is done correctly.

####   

---

#### **Covered in this article:**

#### [**How to troubleshoot your Google Ads Reporting**](#How-to-troubleshoot-your-Google-Ads-Reporting)

* #### [**1.** Make sure your Google Ad Account Integration is connected to the CRM. ](#1.-Make-sure-your-Google-Ad-Account-Integration-is-connected-to-the-CRM.%C2%A0)
* #### [**2.** UTM Tracking template can only be added in one place, like in the Account settings, Campaign, or Ad setup; ](#2.-UTM-Tracking-template-can-only-be-added-in-one-place,-like-in-the-Account-settings,-Campaign,-or-Ad-setup;%C2%A0)
* #### [**3.** Google Ads, Ad-set, and Campaign names need to be unique. If the names are not unique, it will show duplicates in different Ad-set/Ads.](#3.-Google-Ads,-Ad-set,-and-Campaign-names-need-to-be-unique.-If-the-names-are-not-unique,-it-will-show-duplicates-in-different-Ad-set/Ads.-For-example;) [For example;](#3.-Google-Ads,-Ad-set,-and-Campaign-names-need-to-be-unique.-If-the-names-are-not-unique,-it-will-show-duplicates-in-different-Ad-set/Ads.-For-example;)
* #### [Wrong Setup (What not to do)](#Wrong-Setup-%28What-not-to-do%29-[PLEASE-REVIEW-FOR-ACCURACY])
* #### [Correct Setup (What to do)](#Correct-Setup-%28What-to-do%29)
  
  
---

# **How to troubleshoot your Google Ads Reporting**
  
  
## 1\. Make sure your Google Ad Account Integration is connected to the CRM. 

If the integration is connected please proceed to check if the Gmail address given on the integration is the one associated with your Google Ad account.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48248432003/original/VUJN3JbEGt7osLkXqk99TOyEbrlo8bkPRA.png?1661970067)
  
  
Please make sure the email address of the user connected has the maximum amount of permissions **(admin)** in your Google Ad Account.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48248432893/original/mkh9c39KkvP1v3mTsb3Fchx75i56figAeQ.png?1661970338)

  
**Please Note:**

The Gmail account which you have connected in the integration needs to be a user (User or admin) role in the Google Ad account, **it** **can't have a manager role.**
  
  
---

## 2\. UTM Tracking template can only be added in one place, like in the Account settings, Campaign, or Ad setup; 

If it is added at multiple places the tracking template, it will work in the hierarchy of Account > Campaign > Ad. 

  
**Please Note:**

UTM Tracking is **case sensitive** so it needs to follow the template **EXACTLY** with absolutely **NO** capital letters.
  
  
---

## 3\. **Google Ads, Ad-set, and Campaign names** need to be **unique**. If the names are not unique, it will show duplicates in different Ad-set/Ads. For example;

###   
**Wrong Setup (What not to do)**

| **Campaign Name** | Winter Shoes         |
| ----------------- | -------------------- |
| **Campaign id**   | 12345                |
| **Ad Group**      | Sport Shoes 1        |
| **Ad**            | \*Nike Sport Shoes 1 |
| Sport Shoes 2     |                      |
| **Ad**            | \*Nike Sport Shoes 1 |

\* Nike Sport Shoes 1 is listed and spelled the exact same way twice. These would need to be unique.

###   

Let's say **Customer A** is created by **Paid Search.** **Customer A** will be present in the Leads column of Google Ad Reporting displayed as Nike Sports Shoes 1 in two different Ad-sets. This is because the \*Nike Sport Shoes 1 is listed in two different Ad in the table above.

####   

https//example.com?utm\_source=adwords&utm\_medium={NikeSportShoes1}&utm\_campaign={Wintershoes}&utm\_content={sportshoes1}&utm\_keyword={sports}&utm\_matchtype={e}&campaign\_id={12345}&ad\_group\_id={123456789}&ad\_id={sportshoes}

  
###   
**Correct Setup (What to do)**

| **Campaign Name**  | Winter Shoes                   |
| ------------------ | ------------------------------ |
| **Campaign id**    | 12345                          |
| **Ad Group**       | Sport Shoes 1 York             |
| **Ad**             | Nike Sport Shoes 1.1 York logo |
| Sport Shoes 2 John |                                |
| **Ad**             | Nike Sport Shoes 1.2 John logo |
  
  
**Please Note:**

If you were to change the name of your Google Ad Campaign, Ad-set, or Ad, it will not change the existing copy of your UTM parameters but it will attribute to the old parameters instead.   
  
**We recommend creating a new Campaign, Ad-set, and Ad.** In the list view of Google Ad Reporting > HighLevel will update the name but the data will stop attributing sales, leads and ROI as they are picking up on the old UTM parameters.

###   