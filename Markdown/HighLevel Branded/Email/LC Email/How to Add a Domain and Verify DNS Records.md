**Date Updated:** 2024-08-29T01:57:25.000Z

This guide will help you add and verify your email domain.

  
Verifying your domain is really important before you start sending emails. We ask everyone to do this to track opens and clicks, stop spam, and make sure only you and your team can send emails from your domain.

  
**TABLE OF CONTENTS**

* [Step 1: Add Your DomainOnce you are in the Sub-account](#Step-1%3A-Add-Your-DomainOnce-you-are-in-the-Sub-account-%3E-Click-on-Settings-%3E-Email-Services-%3E-Dedicated-Domain-and-IP-%3E-+-Add-Domain.Enter-the-domain-you-want-to-use-in-the-%E2%80%9CEnter-domain-name%E2%80%9D-field,-then-click-)
* [Step 2: Verify Your Domain](#Step-2%3A-Verify-Your-Domain)  
      * [Option 1: Connect Your domain(Auto Configure DNS)](#Option-1%3A-Connect-Your-domain%28Auto-Configure-DNS%29)  
      * [Option 2: Set Up Manually](#Option-2%3A-Set-Up-Manually)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

---

# **Step 1: Add Your Domain**
* Once you are in the Sub-account > Click on **Settings > Email Services > Dedicated Domain and IP > + Add Domain**.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155030257683/original/eBpDo6jvHTTNgDnDaXNI05pdpoVR71twPw.jpg?1722456008)
* **Enter the domain** you want to use in the “Enter domain name” field, then **click "Add & Verify."**  
    
Please note: We recommend using a subdomain for better email deliverability.

---

# **Step 2: Verify Your Domain**

Here are two options for you: Connect through your DNS provider or Set up manually.

* ### **Option 1: Connect Your domain(Auto Configure DNS)**  
This is the easiest method to verify and authenticate your domain. It uses our built-in connection with many top DNS providers to automatically set up DNS records. This way, you can verify and authenticate your domain in just one simple process.  
   1. Click “**Continue**” on the next modal.  
         
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155030257714/original/uwj9p0VMyBDw6SL01nA0_wIkrS19Vt_PTw.jpg?1722456073)  
   2. Our system will detect your DNS provider and then guide you directly to their platform.  
         
   **Note**: The "Configure Domain" option may not be compatible with all DNS providers. If our system is unable to identify your provider, the records will be shown in a modal window. [Click here](#Option-2%3A-Set-up-manually) to manually add the DNS records.  
         
   **The example below shows the DNS provider is Cloudflare.** To move forward, you will need to have the credentials to log into your DNS provider.  
         
   Click “**Authorize domain**” on the next modal.  
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155030257787/original/oTEMnywnxlwP_XOoR4haFwKEjClKuImb_A.jpg?1722456287)  
   3. Login to your DNS provider. This will look slightly different for each provider. This example is Cloudflare. The login method will also be slightly different for each DNS provider.  
         
   The DNS provider in question may ask you to enter a confirmation code emailed or texted to you.  
         
   Click “**Authorize**” on the Cloudflare page.  
         
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155024182925/original/dASFIiw7X2yNMgxetHyCI9i154eWIxYdNg.png?1712635985)  
   4. You will redirected to the domain verification page.  
         
   **Note**: It might take anywhere from 1 to 10 minutes for DNS changes to spread across the internet. Typically, it happens faster, but don't worry if it doesn't happen right away.  
   **DMARC**: If you've already added the policy to your root domain, you can skip adding the DMARC record for the sub-domain.  
         
   If everything is set right you’ll see a **Verified** status like this:  
         
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155024182966/original/lJgc5zwDjmAYfgdlqsFFd-4Ef00pan1idQ.png?1712636006)
* ### **Option 2: Set Up Manually**  
   1. Once you've added the domain, if our system couldn't identify your provider, the records will be displayed for you to see.![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155024182970/original/eYNLZZMFxs-Q1_vJzutB8MfStvdqJroOWg.png?1712636025)Most DNS providers will typically require the following information to set up your DNS records:  
         * **Root domain example:**  
         | Type             | Choose the for each row: TXT, CNAME and MX                                                                                                                                                                                                    |  
         | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  
         | Name or Hostname | Copy and paste the "Name" for each DNS record as follows: Use "@" if your DNS was not verified. Remove the "@" and add your root domain name instead.**Example:** if your domain name is "yourdomain.com", replace "@" with "yourdomain.com". |  
         | Value or Record  | Copy and paste the “Value” shown for each DNS record.                                                                                                                                                                                         |  
         | TTL              | 5 minutes                                                                                                                                                                                                                                     |  
         * **Sub-domain example:**  
                 
         | Type             | Choose the for each row: TXT, CNAME and MX                                                                                                                                                                                            |  
         | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  
         | Name or Hostname | Copy and paste the "Name" for each DNS record.**Example**: If the hostname is mail.yourdomain.com, you may just have to enter the subdomain, which would be "mail". If it's not verified, add the full name like mail.yourdomain.com. |  
         | Value or Record  | Copy and paste the “Value” shown for each DNS record.                                                                                                                                                                                 |  
         | TTL              | 5 minutes                                                                                                                                                                                                                             |  
   2. If everything is set right you’ll see a Verified status like this:  
         
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155024182979/original/omeIHk6jeE3QTNJJEjqI0ZvCWkLLgBc7QQ.png?1712636046)  
   3. You will be redirected to the Dedicated Domain page where you can see the active status.  
         
   **Note:** After your domain is verified, **issuing the SSL certificate** may take between 1 to 10 minutes. Usually, it happens faster, but don't worry if it doesn't happen immediately.  
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155024075588/original/KlEFbcsAmeCfWZFwZnHW5y8l4oepCRgHAw.png?1712388479)

---

# **Frequently Asked Questions**

Currently no frequently asked questions. Submit feedback on this article to help is add questions to this section!

---

# **Related Articles**

* [](https://help.gohighlevel.com/en/support/solutions/articles/155000002369)[Domains in HighLevel](https://help.gohighlevel.com/a/solutions/articles/155000002561?portalId=48000045315)
* [How to setup a dedicated sending domain with LC email](https://help.gohighlevel.com/a/solutions/articles/48001226115?portalId=48000045315)
  
  