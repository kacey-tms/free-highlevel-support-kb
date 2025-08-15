**Date Updated:** 2025-01-22T06:50:46.000Z
  
  
### [Log in to Mailgun](https://app.mailgun.com/app/sending/domains)

  
Make sure the domain is set up for **US** and there's a **green checkmark** next to the domain

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48208234448/original/hQ4e2alh4s_q9lHT5z40nDe5fg6H74dnuA.png?1648486246)

  
**Obtain HTTP webhook signing key:**

  
1\. In the top-right corner of the Mailgun Control Panel, click your Profile Menu to expand the drop-down list of options.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155020788853/original/_jb1iybUD4S3OYX5W-gYw7TZWVY9EqkDIA.png?1708104303)  

  
### 2\. Next, click the API Security option. Alternatively, you can use [this direct link](https://app.mailgun.com/settings/api%5Fsecurity).

### ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155020788827/original/cxT9lUq58GL6OYZRYKwSBCce-s1D_7iFVg.png?1708104258)

  
3\. Copy the **HTTP webhook Signing key**. You will use this as the API key

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155020788820/original/qZPd3x20ggjtR48zLwcFSHiCwYsf0h_vkg.png?1708104236)
  
  
Go to the [Agency settings Email services page](https://app.gohighlevel.com/settings/email%5Fservices):
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48279962136/original/B2HJkrzdKmeChQEF6-kdruFACqTiCGu4bQ.png?1675701596)  

  
**Domain Service** tab:

* Each new location will use the settings based on this configured **HTTP webhook signing key** on the Domain service tab.
* We will also use it to send the **email verification code**

  
Select **Mailgun** as the SMTP Provider![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48279962187/original/w0XyQaMwHu8nvrqjYDFAlyfrO07GKtNvPA.png?1675701610)
  
  
Paste **HTTP webhook signing key** and add ass **API key**, select the **Domain** here, click save

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48279962276/original/WMxrNTB6WKzstuCuw5XPEJJbnkUqJIcZlg.png?1675701637)  

  
Location Settings:

  
* You can configure each location with your client's own Mailgun or your mailgun
* We can use the same Mailgun API and same domain/subdomain for multiple locations
* We can use the same Mailgun API and different domains/subdomains for multiple locations
* We can use the different Mailgun API and domain/subdomain for multiple locations
* You can also set up a unique domain/subdomain for each location to capture cold inbound emails. [Learn more about Cold Email Inbound Setup here](https://help.gohighlevel.com/support/solutions/articles/48001185801-cold-email-inbound-setup).

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48279965088/original/JkIy9dEuTfofeJwsHsu0F3vO1KZeZwyE3w.png?1675702317)
  
  
Click on the Edit ✏️ icon
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48279965291/original/dBydG1vOi9cQPoCEurVc6p9uj4MONMVcGg.png?1675702350)
  
  
Paste the **HTTP webhook signing** **key** here and select the **domain** you configured from the dropdown, Click **Save**
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48279965513/original/cWrQ-BsazwpN1iN7GH5VjSj04fev8lH5tg.png?1675702372)
  
  
If the domain you set up will not show up from the dropdown.

  
1\. Please set up the domain or subdomain under **US, not EU.** 
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48050513712/original/8N26QjIdxTvSEjeFAIA5Lp6vkT-0M2d8iQ.png?1595456311)

  
2\. Check if the mailgun account has added allowed IP in MailGun, so we are not able to pull it. please remove all the IP whitelist, you can add it back later on.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48248684923/original/xk6-sKLoA5BNj5f-WLtNLCQAuZ2aJmLy2w.png?1662053345)  
  
  
Click **Save**
  
  