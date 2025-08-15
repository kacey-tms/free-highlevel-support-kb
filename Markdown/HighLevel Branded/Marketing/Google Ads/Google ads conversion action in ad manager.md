**Date Updated:** 2025-06-04T16:25:53.000Z

HighLevel Ad Manager allows you to **create, manage, and edit Google Ads offline conversion actions** — directly from within the platform. This ensures that your **offline sales, leads, and actions** are properly tracked in Google Ads for better optimisation and reporting.

  
In this article, we’ll cover how to use the **Google Ads Conversion Action Flow** inside Ad Manager.

---

## **TABLE OF CONTENTS**

  
* [Where to find the Conversion Actions section](#Where-to-find-the-Conversion-Actions-section)
* [View existing Google Ads conversions](#View-existing-Google-Ads-conversions)
* [Create a new conversion action](#Create-a-new-conversion-action)
* [Edit or delete a conversion action](#Edit-or-delete-a-conversion-action)
* [Key Notes & Best Practices](#Key-Notes-&-Best-Practices)

  
---

## **Where to find the Conversion Actions section**

  
1. Navigate to **Marketing → Ad Manager**
2. Click on **Settings (gear icon)**  
    
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047727832/original/tLQc97B7dF_Gx6iKsW-A5tbQ7eDwimqN5Q.png?1749033444)**
3. Select **Google Ads** under **Platform Settings**
4. Click on the **Conversions** tab  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047727988/original/bFCZ3XabcFI2X1wjt5ARyXQ9H_iygh4BEQ.png?1749033508)

This will open the **Conversion Actions table view**.

---

## **View existing Google Ads conversions**

  
In the **Conversions** tab, you will see:  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047728138/original/x18MR6wzba__WWd4qgP295FSX2fermEXkw.png?1749033590)  

* A list of all **existing conversion actions** from your connected Google Ads account
* Any **new conversions** you create via Ad Manager
* The table includes columns:  
   * **Conversion Name**  
   * **All Conversion Value**  
   * **All Conversions**  
   * **Conversion Source**

You can use:

* **Search** to filter conversions by name
* **Date Range** filter to view conversions created or updated within a specific time frame

  
---

## **Create a new conversion action**

  
To create a new conversion action:

1. Click **“+ Create a new conversion”**  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047728366/original/_HXMc-rK5LfCNk0Cnatl1ec0I8PGMYuFWA.png?1749033716)
2. Fill out the form in the **Create Conversion modal**:

| Field                               | Description                                                                             |
| ----------------------------------- | --------------------------------------------------------------------------------------- |
| **Conversion Name**                 | A unique name to identify this conversion                                               |
| **Conversion Source**               | Choose the type of offline action (Converted Lead, Purchase, Signup, Add to Cart, etc.) |
| **Count**                           | Many per click (recommended for purchases) / One per click (recommended for leads)      |
| **Value**                           | Use same value per conversion / Use different value per conversion / Don’t use value    |
| **Currency**                        | Select your currency                                                                    |
| **Click-through conversion window** | Choose attribution window (1 to 90 days)                                                |
| **Attribution model**               | Data-driven (preset for offline conversions)                                            |

  
1. Click **Create**.

HighLevel will **create the conversion action in Google Ads** via API - no manual setup needed in Google Ads UI

  
---

## **Edit or delete a conversion action**

  
You can **edit** or **delete** any conversion action created via HighLevel:

1. Click the **3-dot menu** next to the conversion
2. Choose **Edit** or **Delete**  
    
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047728958/original/WNq27h-I9MFDKCyCzfAd8Ndn19KGDHPcxA.png?1749034098)**

**Edit Modal:**  
In the edit modal, you can update:

* Count settings
* Value & currency
* Click-through window
* Conversion source

**Note:**  
Attribution model is fixed to **Data-driven** for offline conversions (per Google Ads guidelines).

  
---

## **Key Notes & Best Practices**

  
* This flow is for **Offline Conversion Actions** \- tracking events like leads, sales, and calls that occur **outside** your website/app.
* All conversions created here are automatically available in your Google Ads account and can be used in campaign reporting.
* Existing Google Ads conversions are automatically imported into this view.
* HighLevel’s tracking will **upload conversion events** to match these conversion actions (via workflows - separate from this setup, refer [from step 8 of this help article](https://gohighlevelassist.freshdesk.com/support/solutions/articles/48001220947-how-to-set-up-google-ad-conversion-actions#Step-8%3A%C2%A0Now-let) for reference).
* Future enhancements will add **Google Tag Manager (GTM)** integration for **website conversion actions**.
  
  