**Date Updated:** 2025-07-24T17:35:30.000Z
  
  
Business users are able to process payments via Razorpay, a payment provider popular in India. This integration is available as a marketplace application under App Marketplace menu inside a sub-account and also available upon clicking on the Search for More options inside Payments -> Integrations

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026996886/original/cGM38lkSCd8himqlO0oJsISt_rPGSvI_eQ.png?1717409062)

  
The integration provides capabilities to accept one time, custom amounts as well as recurring payments across all channels like order forms, invoices, payment links, forms, contacts page among others. This also provides subscription management like cancellation, updating a card on file or refund related capabilities

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026996913/original/24M_t65AjM_C10oGXduK3C897S57ED9Jvg.png?1717409084)
  
  
Sub-account users will be able to install the application from the App Marketplace, authenticate using the necessary API keys, and grant necessary permissions to start accepting payments using Razorpay.

###   

To successfully connect Razorpay with your system, please follow these four essential steps:

1. **Install the Razorpay App**  
Navigate to the **App Marketplace** and install the Razorpay application.
2. **Authenticate Using API Keys**  
Copy your Razorpay API keys from the Razorpay dashboard (`Accounts & Settings → API Keys`) and paste them into the app authentication page.
3. **Configure Webhooks**  
In your Razorpay dashboard (`Accounts & Settings → Webhooks`), add the following Webhook URL:  
`https://backend.leadconnectorhq.com/razorpay/webhook`  
Be sure to enable **all payment-related events** for proper syncing.
4. **Register and Whitelist Your Domain**  
   * In your GHL dashboard, go to `Settings → Business Profile → Branded Domain` and register the domain you're using. Make sure to verify and click on update information.  
   * Next, log in to your Razorpay dashboard and go to `Accounts & Settings → Business Website Details → Add Additional Website/App Details`.  
   Add the same branded domain here. Razorpay will verify and enable it.  
   > **Note**: Razorpay only allows payment acceptance from domains that have been whitelisted on their dashboard.
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026997128/original/t9TZ7tccQzpZRWN43mOia_7L36jxKsgjJA.png?1717409204)
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026997230/original/dPoQMqwLdRm-suaWk-lrOlU8iKKfIcRorw.png?1717409258)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050371865/original/0K6GPMGTrW4t-SZJsA4pnDxEnDfOMM9k5w.png?1753358687)
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050371729/original/ZyWe2x3yglTf1I1OQZ4tpWw-MNA6oBHSqw.png?1753358576)  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050371757/original/9iLBTndWU4xo2kimBb9BS1hPgxMToZjcfw.png?1753358602)
  
  
Once the app is installed, the Authentication page would be displayed which would require you to plug in your API keys from the Razorpay dashboard. Navigate to **Accounts & Settings -> API keys** to get the API keys from your Razorpay dashboard. 

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026999032/original/3zOKWp0Fvr9avNgbDH-bVS_c2Mnt-LBe4Q.png?1717410595)
  
  
For smooth functioning of the integration in fetching the transaction statuses from Razorpay, it is required that you also paste the given link in your razorpay dashboard under Webhooks (**Accounts & Settings -> Webhooks**). Make sure that you select the following webhooks events to not lose out on any feature

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155027000787/original/4a6-JrR2U35cs14zYq_UoWzPW9ivayIGjQ.png?1717411942)

  
Also, add [](//link.fastpaydirect.com)any branded domain that you are using inside the Razorpay dashboard (**Accounts & Settings -> Business website details**)
  
  
The application would in no way differ from the existing payment integrations like Stripe/NMI/[Authorize.net](http://authorize.net/) and would have full capabilities for payments including post purchase automations like automated sales receipts, refunds, payment received and order submitted triggers or giving discounts via coupon codes