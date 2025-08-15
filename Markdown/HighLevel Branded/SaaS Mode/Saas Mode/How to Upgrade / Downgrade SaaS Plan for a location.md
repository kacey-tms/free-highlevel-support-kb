**Date Updated:** 2025-06-17T00:17:58.000Z
  
  
If you are on the Pro Plan and have a sub-account in SaaS mode, you can enable any of the 3 SaaS plans for them. Once added to a SaaS plan from the system, their Subscription is handled at the Stripe level. You can toggle on a setting that lets them **Upgrade (only)** their Subscription on their end. If you need to upgrade/downgrade their account on your side, you must do this from Stripe.
  
  
#### **Covered in this Article:**

#### [**How to allow Customers to upgrade their SAAS plan themselves?**](#How-to-allow-Customers-to-upgrade-their-SAAS-plan-themselves?)

#### [**How to change the SaaS plan from your end:**](#How-to-change-the-SaaS-plan-from-your-end%3A)

#### [Finding the Stripe Customer](#Finding-the-Stripe-Customer)

#### [Changing the subscription plan](#Changing-the-subscription-plan)

#   

---

## **How to allow Customers to upgrade their SAAS plan themselves?**

Agencies can now allow their SaaS clients to upgrade their SaaS subscriptions from the company billing page. This setting is controlled on the Agency SaaS Configurator. Once you mark the checkbox next to **Allow clients(sub-accounts) to upgrade to a higher plan, Subscription your** SAAS clients will then be able to Upgrade their subscription from within their Account **Settings> Company Billing.**
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48283842596/original/Sx4a2Gv2CZqUQUl7bVWULvTfkCwr7TTR2A.png?1677425334)

  
**Please Note:**

This will apply this setting to all SAAS accounts that will be created using your SAAS configurator moving forward.
  
  
This setting can also be personalized at a per-client level by Going to the **Agency Sidebar> Sub-Accounts> Scroll to the specific client> Click on their name or on Manage Client:**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48283851954/original/-B4BSvLsb6RMYvd1AhFHMdIAMamU3AE2sQ.png?1677441616)  
  
Please Scroll down to subscription details and check to mark the checkbox to Allow them to upgrade. This setting will only apply to this sub account and not all SAAS accounts created using your SAAS configurator moving forward. sub-account,  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48283851923/original/skWGGh1eIvugQPC_-2bE1iv7TnkEc4ZQyg.png?1677441510)

  
Once this checkbox is marked, your client will see a **Modify Subscription** button below their subscription details in **Settings> Company Billing:**

**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48283852316/original/kdvFs96IApUgGTbi_WeBUh9nfsvgVWHd-A.png?1677442010)**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48283852342/original/E6y2_tIAISvFbLR_-5NCYxxgSlTTBaQxsQ.png?1677442101)  

They will then be allowed to choose between the higher-tier plans you have configured in your SAAS configurator.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48283852334/original/lKP4jz6YAVujqZjQTV06n3P4axQCLxZQCw.png?1677442065)

  
Upon choosing their desired plan, they will see a confirmation message which will also allow them to choose between the Monthly and the annual variant of your created plan:  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48283852490/original/kFYGhwqxIrVkK_C_8uqXFaTt6SBcEmhZZQ.png?1677442334)

  
Clicking on **Confirm & Pay** will charge them and you can then unlock the features associated with that plan in their account.  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48283852530/original/RMElQ7DTY-E66queGSyUWLBgJ01MOLS23A.png?1677442426)

---

## **How to change the SaaS plan from your end:**

In this example, we have 3 SaaS plans, Standard, Professional, and Premium. Each higher plan has more features offered.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179188952/original/xg82nBBNc8zEEx0Q6jvtLt240q4mCO6EIg.png?1642180292)

  
We have a location on the Standard plan with basic features only.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179189995/original/MTfPSGTUV_DzOktBCvriVc4ymTDBR-Oc6Q.png?1642180555)

  
To upgrade this location to the Professional plan, we will need to go into our Stripe account and open the customer associated with this location.

###   
**Finding the Stripe Customer**

You can search the customer in Stripe using your client's email. However, the preferred method is to search for the invoice ID for this location and get the customer ID from there.

  
1\. Go into Subaccount Settings > Company Billing and click "View" for any invoice shown in the Billing History

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179191623/original/YgHpXmm6kMJ-ZXFtH_ampYMSw6Qq10CdJQ.png?1642180932)

  
2\. Copy the invoice number

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179191948/original/28_J0a_IQe8l30wGT2UWHt0iDyTkxAwCqQ.png?1642181036)

  
3\. Search for the invoice number on Stripe and click on the invoice to open the details

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179192675/original/IxhpfGaIOK5uxgGt3WgUba37jlPIW6ybQg.png?1642181198)

  
4\. Click on the customer email shown in the 'Billed to' column on the invoice; it will take you to the customer's profile in Stripe

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179193172/original/jJl6AoSWYy6CzP-DRhLJOuy9aCe_S1tF0Q.png?1642181316)

  
### **Changing the subscription plan**

Now that we are in the customer profile on Stripe, we have updated the client's subscription plan.

  
1\. Click on the pencil icon to update the subscription plan

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179204701/original/tW6N-xWl8eQg9Slvwr0PISwUriI_BCJgzg.png?1642183950)

  
**2\.** Remove the current price and add the new plan's price

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179205217/original/qgQsQVyZBOJFYg9daBCfeUTldUzQNuxs2A.png?1642184088)

  
3\. Review your changes, prorate changes if you want to adjust the billing difference in the next invoice, and then hit the update button

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179205549/original/YHLzV6ZB7SuwdPZgJPqUR47CJ458GKHFgQ.png?1642184206)

  
4\. On your agency account, go to the Accounts tab > View details for the location. The plan is now upgraded, **but** you still need to update their accessible features according to the new plan:

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179200049/original/j2uNrKdUuGRToQ7uQSxL_inhtBd_CYkXlw.png?1642183048)

  
5\. Save the updated feature set for this location, and then you're good to go!

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48179200337/original/oun45XOJp3E2WWwfY5NH_zIyebPvLT-YOQ.png?1642183137)

  