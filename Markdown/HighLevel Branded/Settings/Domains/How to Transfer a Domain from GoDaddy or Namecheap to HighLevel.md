**Date Updated:** 2025-07-11T09:24:36.000Z

This guide walks you through how to transfer your existing domains from registrars like GoDaddy or Namecheap into HighLevel using the Domain Transfer-In feature. By the end of this article, you’ll understand how to configure the feature, perform a successful domain transfer, and manage your DNS settings—all from one place. Whether you’re centralizing your workflows or improving DNS security, this guide ensures you follow each step with clarity and confidence.

---

**TABLE OF CONTENTS**

* [What is Domain Transfer-In](#%E2%80%8B%E2%80%8BWhat-is-Domain-Transfer-In)
* [Key Benefits of Domain Transfer-In Feature in HighLevel](#Key-Benefits-of-Domain-Transfer-In-Feature-in-HighLevel)
* [How to Configure Domain Transfer-In](#How-to-Configure-Domain-Transfer-In)  
   * [Step 1: Enable Domain Purchase (Agency Settings)](#Step-1%3A-Enable-Domain-Purchase-%28Agency-Settings%29)  
   * [Step 2: Enable Domain Purchase for Sub-Accounts](#Step-2%3A-Enable-Domain-Purchase-for-Sub-Accounts)  
   * [Step 3: Enable Domain Transfer-In in Labs](#Step-3%3A-Enable-Domain-Transfer-In-in-Labs)  
   * [Step 4: Initiate Domain Transfer](#Step-4%3A-Initiate-Domain-Transfer)  
   * [Step 5: Complete the Eligibility Check](#Step-5%3A-Complete-the-Eligibility-Check)  
   * [Step 6: Review or Upload DNS Records](#Step-6%3A-Review-or-Upload-DNS-Records)  
   * [Step 7: Finalize the Transfer](#Step-7%3A-Finalize-the-Transfer)  
   * [Step 8: Approve the Transfer at Registrar End](#Step-8%3A-Approve-the-Transfer-at-Registrar-End)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# **What is Domain Transfer-In**

  
**Domain Transfer-In** is a built-in HighLevel feature that allows users to move domain ownership and management from third-party registrars (such as GoDaddy, Namecheap, etc.) into the HighLevel platform. This simplifies your workflow by letting you purchase, transfer, renew, and manage DNS records without ever leaving your sub-account. The Domains page acts as your centralized dashboard for all domain activity, improving visibility and control.

  
When you initiate a domain transfer, HighLevel guides you through a 5-step process—starting with domain entry and ending with approval from your current registrar. The system automatically checks transfer eligibility, allows DNS record import or review, and ensures a secure finalization using an EPP (authorization) code. Once complete, the transferred domain integrates instantly with your websites, funnels, client portals, and email systems—all within HighLevel.

---

## **Key Benefits of Domain Transfer-In Feature in HighLevel**

  
* **Centralized Control:** Manage purchases, renewals, DNS settings, and product connections directly from your sub-account’s Domains dashboard.
* **Zero Downtime with DNS Verification:** Preserve critical services like email and websites by reviewing or importing DNS records during the transfer process.
* **Transparent Pricing with Built-in Renewals:** Transfer fees are fixed and clearly shown upfront. You also gain an additional year added to your existing domain’s renewal period.
* **Secure Management Without External Logins:** No need to log into GoDaddy or Namecheap post-transfer—manage all domain settings directly within HighLevel.
* **Instant Product Integration:** Transferred domains instantly connect to funnels, websites, blogs, email tools, and client portals without manual mapping.

---

## **How to Configure Domain Transfer-In**

  
Follow these detailed steps to enable and complete a domain transfer into HighLevel. This guide also includes important prerequisites to ensure a smooth experience.
  
  
### **Step 1: Enable Domain Purchase (Agency Settings** **)**

  
* **Switch to Agency View** by clicking the location dropdown at the top-left corner of your screen and selecting **Agency**.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049655111/original/kkNHVEyw7rIp7r7fQMPmxMkqsdgtndl01Q.png?1752149162)
* Navigate to Settings → Company → Domain Purchase. Toggle the setting **ON** to activate domain purchasing functionality across the platform.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049656223/original/yZFfg9b7sV1GCbdc1JaLAPvjbRKt27KBOA.png?1752149798)

### **Step 2: Enable Domain Purchase for Sub-Accounts**
  
  
* Go to Settings → Domain Purchase  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049656610/original/0MkI94ygQEeV_2d8upX33KaQapoezt23Ag.png?1752149973)
* Enable domain purchasing individually for each sub-account that will use the Domain Transfer-In feature.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049656623/original/XbeJO_fHxPVuiQGQzY-OINPzDn-liSIuOA.png?1752149988)
  
  
### **Step 3: Enable Domain Transfer-In in Labs**

  
* Go to Settings → Labs → Sub-Account  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049657017/original/_isnB-0iScduWVAaQeSshm78wqjnDZSLrw.png?1752150286)
* Locate **Domain Transfer-In** and click **Manage**  
    
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049657337/original/rEG9FccerRt3bI15Dh1d89YoCOgFvWufIw.png?1752150501)**
* Choose the sub-accounts where this feature should be active.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049657637/original/MV0pRo4jhh4ZVEGgDkBuKLYsHgqF_ItrBg.png?1752150769)
  
  
**Before starting the transfer, ensure:**

You must be an Admin of the sub-account.

The domain should be at least 60 days old and not in a locked or pending status.

You must have access to your registrar account (e.g., GoDaddy or Namecheap).

Your HighLevel Wallet must have sufficient funds for the transfer fee.

You should be able to unlock the domain, disable DNSSEC, and turn off Whois Privacy at your registrar.

It’s recommended to export your current DNS zone file for backup or import.
  
  
### **Step 4: Initiate Domain Transfer**

  
* Go to the **Domains page** within the relevant sub-account.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049688031/original/DWWPghvyNVS_xAL5jKWqvi954hXAtihFEg.png?1752193618)
* If the domain already exists as external, click **Transfer-In**.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049688053/original/Fe3ZCVo7x9lO4IBKNb2RLnaL07Wpb-rRIA.png?1752193788)
* Otherwise, click **Purchase/Transfer Domain → Transfer Domain**.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049688057/original/vi9WtCLcflYyby-JreRcSAFcSx9lzoNsRA.png?1752193826)
  
  
### **Step 5: Complete the Eligibility Check**

  
* The system will verify whether the domain is eligible for transfer. You’ll also see the transfer fee and domain expiration details here.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049690033/original/pe7bEjMtg9gH4wQvob2pns7XEYIfSENq0g.png?1752203674)

  
### **Step 6: Review or Upload DNS Records**

  
* Choose to auto-scan DNS records or upload a zone file from your registrar. Double-check all entries—especially for email, website, and CNAME records—to avoid service disruptions.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049690332/original/bumiXWCPAl5xk0Z5VETFER1BWts5Daqzcw.png?1752205161)
  
  
### **Step 7: Finalize the Transfer**

  
* At your current registrar:  
    
   * Unlock the domain  
   * Disable DNSSEC  
   * Turn off Whois Privacy  
   * Copy the EPP (authorization) code
* Paste the EPP code into HighLevel and confirm the transfer.
* The transfer fee is deducted from your HighLevel Wallet.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049690401/original/OP4XNcybo4jXOq2oQvgqfrjXbFULNiftrg.png?1752205434)
  
  
### **Step 8: Approve the Transfer at Registrar End**

  
* Your registrar may send you an approval email or require you to manually approve the transfer in their dashboard. Once approved, the domain becomes internal and fully manageable within your HIghLevel account.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049690466/original/a47gEtFu1eoYG_CmaegQLYfLqQK_sLWMEg.png?1752205700)

---

## **Frequently Asked Questions**

  
**Q: Will my website or email go down during the transfer?**

No, as long as DNS records are reviewed and correctly configured during the transfer process, there should be no downtime.

  
**Q: How do I get my domain’s authorization (EPP) code?**

Log into your current domain registrar’s dashboard. The EPP code is usually available in the domain management section.

  
**Q: Can I transfer any domain extension (TLD) to HighLevel?**

HighLevel supports most common TLDs like .com, .net, .org. However, some country-specific domains like .in, .co.uk, and .tv are not supported.

  
**Q: What happens if I make a mistake with my DNS records?**

You can review and edit DNS records during the transfer process. If needed, you can also make changes post-transfer under DNS settings (for internal domains).