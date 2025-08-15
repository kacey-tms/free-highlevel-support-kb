**Date Updated:** 2024-05-31T15:00:03.000Z

Adding a domain to a WordPress site is necessary to make the website accessible to the public through that Domain. A domain serves as the website's address, and visitors can use it to access the site.

  
The article provides step-by-step instructions for adding a primary domain and additional domains to a WordPress site.

  
**TABLE OF CONTENTS**

* [Adding Primary Domain in WordPress Dashboard:](#Adding-Primary-Domain-in-WordPress-Dashboard%3A)  
   * [Step 1: Add Your Domain Name](#Step-1%3A-Add-Your-Domain-Name)  
   * [Step 2: Configure SSL Certificate](#Step-2%3A-Configure-SSL-Certificate)  
   * [Step 3: Update DNS](#Step-3%3A-Update-DNS)
* [Adding Sub Domain in WordPress Dashboard:](#Adding-Sub-Domain-in-WordPress-Dashboard%3A)  
   * [Step 1: Add Your Sub-Domain Name](#Step-1%3A-Add-Your-Sub-Domain-Name)  
   * [Step 2: Update CNAME and A record with your DNS provider](#Step-2%3A-Update-CNAME-and-A-record-with-your-DNS-provider)
* [Comprehensive Domain/Sub-Domain Dashboard:](#Comprehensive-Domain/Sub-Domain-Dashboard%3A)

[](#Topic2)

---

# **Adding Primary Domain in WordPress Dashboard:**

Go to your Sub-Account-> Sites-> WordPress Dashboard. In the Dashboard you will see a section for adding Domains/subdomain. Click on 'Add Domain' Button to proceed.  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026889582/original/EkpDv21hmqThD--EwH4M4I-hE4W9csSwyg.png?1717145194)  

## **Step 1: Add Your Domain Name**

1. Navigate to the domain management section in your WordPress hosting dashboard.
2. Enter your desired domain name.
3. Our system will automatically verify if the domain is already associated with another location or agency.
4. If the domain is available, proceed to the next step.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026889970/original/MjTA50ZL_e_Aq63xDr01v_2X3Bek64IQFA.png?1717145448)

  
## **Step 2: Configure SSL Certificate**

1. After your domain is verified, you will need to configure your SSL certificate.
2. Add the provided TXT records to your DNS provider.
3. Once the TXT records are successfully added and verified, you can move on to the final step.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026890081/original/jvDFyZPA87UqHBxsEtgj1B8l9Ct5TZujug.png?1717145549)

  
1. While most SSL Records propagate within an hour, global updates take upto 48 hours.
2. Configure your TTL Value to 600 ms or the lowest value possible for optimal ssl record propagation. 

###   

## **Step 3: Update DNS**

1. In this step, you will need to update your DNS settings.
2. Add the provided CNAME and A records to your DNS provider.
3. Once the records are successfully added click on 'Verify DNS Records' button.
4. Go to the dashboard and Mark your Domain as Primary.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026890939/original/bana4qsBHqDH63yLMHi0ge7E275iKgY3iA.png?1717146143)

  
1. If your DNS Provider is Cloudflare, please turn off Proxy Settings
2. While most DNS updates activate within an hour, global updates take upto 48 hours.
3. Configure your TTL Value to 600 ms or the lowest value possible for optimal DNS record propagation.

  
# **Adding Sub Domain in WordPress Dashboard:**

Adding sub-domain is similar to adding your Domain. The SSL certificate for additional domains will be Verified in the Update DNS step and hence adding the TXT records is not required. 

  
## **Step 1: Add Your Sub-Domain Name**

1. Navigate to the domain management section in your WordPress hosting dashboard and enter your desired domain name.
2. Our system will automatically verify if the domain is already associated with another location or agency. If the domain is available, proceed to the final step of updating DNS records.

## **Step 2: Update CNAME and A record with your DNS provider**

1. Add the provided CNAME and A records to your DNS provider.
2. Once the records are successfully added click on 'Verify DNS Records' button.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026892143/original/cDKrS-1v1iSnRRwt6-b5ZuBDGu75RefZ9w.png?1717147061)
  
  
# **Comprehensive Domain/Sub-Domain Dashboard:**

Our new dashboard offers a comprehensive overview of domain management. 

* **SSL Issuance Status:** Monitor the status of your SSL certificate issuance to ensure it is properly configured using the 'SSL issued/ SSL Not Issued' tags.
* **DNS Record Verification:** Check the verification status of your DNS records to confirm they are correctly set up using the 'Verified/ Not Verified' tags.
* **Domain Management:** You can add up to 5 domains or sub-domains. Designate one as your primary domain for better organisation.
* **Easy Prefix Adjustment:** Easily switch between www and non-www prefixes with a simple adjustment in the dashboard using the 'Change prefix to WWW/ Remove WWW Prefix' option.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155026892814/original/S-oyWWLKWjNB7CPKvMB6GC8XSmGRHD_6KQ.png?1717147478)

If you need to delete and re-add a domain, please note that this process might take some time.

  
---

Our enhanced domain management flow ensures that adding and managing your domains is as smooth and efficient as possible. With the new streamlined steps and a powerful dashboard, you can enjoy greater control and simplicity in managing your WordPress hosting services.

For further assistance or if you have any questions, please contact our support team. Enjoy the new domain management experience!

  
#   

###   