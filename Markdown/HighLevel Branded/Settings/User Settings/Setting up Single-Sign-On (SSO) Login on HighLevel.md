**Date Updated:** 2025-07-23T16:35:02.000Z

In this article, you'll learn how to setup integrate your HighLevel account with an external SSO provider to offer a Single Sign On experience to your users. 

  
Here's a short demo of what the Login experience with SSO looks like.
  
  
### **TABLE OF CONTENTS**

* [What's the price of enabling this feature?](#What's-the-price-of-enabling-this-feature?)
* [Things to know before activating this feature:](#Things-to-know-before-activating-this-feature%3A)
* [How do I add users from my SSO identity provider's (IDP) user database to GHL?](#How-do-I-add-users-from-my-SSO-identity-provider's-%28IDP%29-user-database-to-GHL?)
* [How do I configure SSO after the feature has been activated?](#How-do-I-configure-SSO-after-the-feature-has-been-activated?)
* [Okay I'm interested. What's the process of setting it up?](#Okay-I'm-interested.-What's-the-process-of-setting-it-up?)
* [What happens if the user's email gets updated on the SSO IDP user database?](#What-happens-if-the-user's-email-gets-updated-on-the-SSO-IDP-user-database?)

  
### **What's the price of enabling this feature?**

This feature is available as a part of $497 plan. 

  
### **Things to know before activating this feature:**

* To use the SSO Login feature, your agency must be on $497 plan, and must have a whitelabel domain enabled.
* We only support one SSO integration at the agency level. This means all users across all sub-accounts within the agency share the same SSO login experience.
* We currently support OIDC standard only. We do not support SAML.
* Users are not auto-created in HighLevel through the SSO Integration. You will need to setup the user creation using APIs. The next section elaborates on this.

  
### **How do I add users from my SSO identity provider's (IDP) user database to GHL?**

**Step 1**: Create a [**Private Integration**](https://help.gohighlevel.com/support/solutions/articles/155000003054-private-integrations-everything-you-need-to-know#What) token with 'Create or Edit Users' scope enabled.

**Step 2**: Use the **[Create Users API for SSO](https://drive.google.com/file/d/1G334sJtEVpCd3KyV%5FZyt2%5F8MnYSS7IN-/view?usp=sharing)** (open this file on [**Swagger**](https://editor.swagger.io/) for better radability) to create/update users on HighLevel. Make sure that the parameter "externalUserId" is updated as per the unique user ID on your SSO IDP's user database.

  
### **How do I configure SSO after the feature has been activated?**

Once the feature is activated on your account, Agency Owner will be able to configure SSO under Agency Settings > Team page. Here's a demo video of configuring SSO Integration with Auth0.
  
  
### **Okay I'm interested. What's the process of setting it up?**

1. **Step 1**: This feature is currently being tested in Private Beta. To enable this feature, please confirm you have a white label domain setup & part of $497 plan and drop an email to **[crm-users@gohighlevel.com](mailto:crm-integrations@gohighlevel.com)** with your [relationship number](https://help.gohighlevel.com/support/solutions/articles/48001204536-how-do-i-find-my-agency-s-relationship-number-).
2. ****Step 2: You must update your existing users with the externalUserID [as mentioned above](https://help.gohighlevel.com/support/solutions/articles/155000004387-setting-up-single-sign-on-sso-on-highlevel#How-do-I-add-users-from-my-SSO-to-GHL?).**
3. ****Step 3: You must configure SSO [as mentioned above](https://help.gohighlevel.com/support/solutions/articles/155000004387-setting-up-single-sign-on-sso-on-highlevel#How-do-I-configure-SSO-after-the-feature-has-been-activated?). Once done, all your users will see the "SSO Login" option on your white-labeled login page.**

  
### **What happens if the user's email gets updated on the SSO IDP user database?**

HighLevel relies on the externalUserId to uniquely identify the user at the time of login. If the user's email is updated on the IDP database after initially creating the user, HighLevel will automatically update the user's email on HighLevel's side the next time the user logs in.

  