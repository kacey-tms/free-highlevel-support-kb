**Date Updated:** 2025-07-28T18:39:19.000Z

Email marketing is a great way to reach customers and increase sales. But if you're not careful, you could end up in trouble. A dedicated sending domain gives you control over what appears to be coming from your business. That means you can avoid spam filters and other issues that might get your messages caught by unwanted mail servers.  
  
Don't let your email marketing efforts go unnoticed! Get started right away with a dedicated sending domain.

  
**IMPORTANT:** Dedicated sending domains are **only applicable** to the users in the **[LC Email system](https://help.gohighlevel.com/en/support/solutions/articles/48001222501).**  
  
If you are using a new domain that has never been used for email **please make sure to warm up your domain before emailing to a large list.** Failure to do so will results in poor deliverability results.
  
  
**IMPORTANT**: If you wish Set Up other SMTP Providers, refer to  [Setting Up SMTP Providers](https://help.gohighlevel.com/support/solutions/articles/48001059689-setting-up-smtp-providers)

---

**TABLE OF CONTENTS**

* [What is a Dedicated Sending Domain?](#What-is-a-Dedicated-Sending-Domain?)[](#Configuring-Dedicated-Sending-Domains)
* [Configuring Dedicated Sending Domains](#Configuring-Dedicated-Sending-Domains)
* [Troubleshooting Dedicated Sending Domains](#Troubleshooting-Dedicated-Sending-Domains)[](#Frequently-Asked-Questions)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What is a Dedicated Sending Domain?**

  
A dedicated sending domain allows you to send emails that appear to be coming from your brand, which can help you maintain a better reputation with email services. Any sub-account or agency can create a dedicated sending domain, and it's quick and easy.

  
By default, all emails sent from our platform will show the name of our email-sending servers in the "**sent on behalf of**" or "**sent via**" email headers:

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48265938968/original/spw7PyvCIf6DlxRXiukwE1KRAbxsW5nK9w.png?1669638686)

---

## **Configuring Dedicated Sending Domains**

  
You can create multiple sending domains under your account and use different domains for different email-sending actions such as 1-to-1 emailing, emails sent from workflows, marketing campaign emails, and Payment and Invoices emails.
  
  
### **Step 1:** Navigate to Email Services

  
* Navigate to Settings > Email Services
* Click the "Dedicated Domain and IP" button.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039358860/original/SDAmMz_uAVt2ybizJ-_9H4TdvCGO9uG8bw.png?1736193889)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039359007/original/fPkMuNjtNulufDsHraKqi_RhiT7kVj6i7g.png?1736194222)
  
  
### **Step 2:** Add Domain Information

  
* Click the "Add Domain" button to begin configuring your sending domain.
* Enter the sub-domain you want to use for your dedicated sending domain.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039359484/original/eF1kHVNdn9F8E4LQc47YnPLKxFqETCQFag.gif?1736195532)

  
**What is a Sub-Domain?**  
  
Sub-domains are variants of your root domain.  
  
**For Example:** If you wanted to use the root domain "agency123.com" to send emails, you an create sub-domains such as "emails.agency123.com" or "no-reply.agency123.com", and use these sub-domains in different communication or marketing campaigns.  
  
You can create as many sub-domains as you like by adding unique words in front of the root domain and then configuring the DNS records in your hosting provider settings.
  
  
### **Step 3:** Verify DNS Records

  
Once you've added your sub-domain, you will need to verify your DNS records. You will have the option to either allow HighLevel to auto-configure your DNS records, or enter your DNS records manually.

  
If HighLevel is unable to automatically configure your DNS records, you will need to add them manually.

  
**REMEMBER:** The propagation process can take up to 24 hours. If it has been longer than 24 hours, please double-check your DNS settings by following the process above.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039360349/original/P-zGHtE40RWBS1c78K9-QxTVmAZcGYspOA.gif?1736198292)
  
  
#### **Manually Adding DNS Records**

  
To add your DNS records manually, you will need to create the DNS records in your hosting provider's dashboard where you manage your domains. You will be given specific information from HighLevel, like the information you see in the screenshot below, that you will use to create your DNS records.

  
To learn more about manually adding your DNS records, click here to read a more detailed help article.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155039360663/original/HzBGtABLJsce2UkbD9t9VMG5rxqjnhBPfg.png?1736199195)  

  
**Click any of the links below for instructions for some common DNS providers:**

  
| [GoDaddy](https://www.godaddy.com/help/manage-dns-zone-files-680)[](https://support.google.com/a/answer/48090?hl=en)[Google Domains](https://support.google.com/a/answer/48090?hl=en)[](https://www.hostgator.com/help/article/manage-dns-records-with-hostgatorenom)[](https://www.hostgator.com/help/article/manage-dns-records-with-hostgatorenom)[Hostgator](https://www.hostgator.com/help/article/manage-dns-records-with-hostgatorenom)[](https://help.hover.com/hc/en-us/articles/217282457-How-to-Edit-DNS-records-A-CNAME-MX-TXT-and-SRV-Updated-Aug-2015-)[Hover](https://help.hover.com/hc/en-us/articles/217282457-How-to-Edit-DNS-records-A-CNAME-MX-TXT-and-SRV-Updated-Aug-2015-)[](https://www.namecheap.com/support/knowledgebase/article.aspx/9214/31/cpanel-email-deliverability-tool--spf-and-dkim-records/)[Namecheap](https://www.namecheap.com/support/knowledgebase/article.aspx/9214/31/cpanel-email-deliverability-tool--spf-and-dkim-records/)[Squarespace](https://support.squarespace.com/hc/en-us/articles/205812348-Opening-Advanced-DNS-settings)[](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resource-record-sets-editing.html)[](https://support.squarespace.com/hc/en-us/articles/205812348-Opening-Advanced-DNS-settings) | [AWS](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resource-record-sets-editing.html)[](https://developers.cloudflare.com/dns/manage-dns-records/how-to/create-dns-records/)[Cloudflare](https://developers.cloudflare.com/dns/manage-dns-records/how-to/create-dns-records/)[](https://www.bluehost.com/help/article/dns-management-add-edit-or-delete-dns-entries)[Bluehost](https://www.bluehost.com/help/article/dns-management-add-edit-or-delete-dns-entries)[](https://www.hostinger.com/tutorials/how-to-use-hostinger-dns-zone-editor)[Hostinger](https://www.hostinger.com/tutorials/how-to-use-hostinger-dns-zone-editor)[](https://www.inmotionhosting.com/support/domain-names/create-cname-record/)[InMotion](https://www.inmotionhosting.com/support/domain-names/create-cname-record/)[Hostwinds](https://www.hostwinds.com/guide/how-to-change-cname-record/) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

---

## **Troubleshooting Dedicated Sending Domains**

  
While setting up your dedicated sending domains, you may run into some issues that can be resolved without reaching out to the HighLevel support team. Below are some common issues that you may be experiencing when setting up your dedicated sending domains.

  
* **Error Message Reading: 'Domain already pointing to email server!'**  
    
You may see an error message that is claiming your domain is already pointing to an email server. This means that your email domain already has DNS records connected to a different service, and you will need to disconnect the domain before you can connect it to your HighLevel account.  
    
Any MX or SPF records, even if they are HighLevel records, will cause the system to reject the domain, so we will need to remove them.  
    
You can look up the domain MX and SPF records using various tools across the internet. The following link is a free tool that can help you with MX and SPF lookup: <https://mxtoolbox.com/SuperTool.aspx>

  
---

## **Frequently Asked Questions**

  
**Q: How Do I Choose a Sending Domain Name for My Account?**

It would be best if you used a unique subdomain that is not used for any other purpose. A subdomain is a secondary part of your root domain. For example, if your dedicated sending domain is **hello@mg.yourbrand.com**, your subdomain would be the **“mg”** portion of that domain.
  
  
**Q: How Do I Set Up a Dedicated IP Address?**

Setting up a dedicated IP Address is an entirely different process. [Click here to learn more about setting up dedicated IP Addresses.](https://help.gohighlevel.com/en/support/solutions/articles/155000001152)
  
  
**Q: What do I do if some of my domain's DNS records are not verified yet?**

You will need to force the verification process manually. If after doing this, the DNS records still are not verified, you may have to resolve the issue by contacting your hosting provider.
  
  
**Q: How do I generate an SSL Certificate for dedicated sending domains?**

When your domain is verified, the SSL Certificate should be automatically generated.

  
If the domain is showing as verified, but there is no SSL certificate, you may need to re-verify it by going through the entire verification process again. If that doesn't work, contact your hosting provider to see if there is an issue with your domain or if they can help generate the SSL certificate for you.

  
**Q: What if my domain has a wildcard DNS record?**

If your domain has a wildcard record (e.g., \*.yourdomain.com), you'll see a "pre-existing record" error when trying to set up a subdomain like mail.yourdomain.com.

Because wildcard records act as catch-alls, so any subdomain already "exists" by default.

  
To resolve this, you can remove the wildcard record temporarily and add it back after the dedicated domain is verified. You can also manually add DNS records for each subdomain to override the wildcard.

  
---

## **Related Articles**

  
* [Email Sending Guide: Email Best Practices & Email Warm Up](https://help.gohighlevel.com/en/support/solutions/articles/155000001021)

  