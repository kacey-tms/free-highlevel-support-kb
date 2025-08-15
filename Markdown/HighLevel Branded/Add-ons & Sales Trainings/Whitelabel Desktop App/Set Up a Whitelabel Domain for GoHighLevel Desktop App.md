**Date Updated:** 2025-06-21T02:17:22.000Z

---

**TABLE OF CONTENTS**

* [Why do I need to whitelabel the desktop web app?](#Why-do-I-need-to-whitelabel-the-desktop-web-app?)
* [How to Whitelabel the Desktop App](#How-to-Whitelabel-the-Desktop-App)
* [Troubleshooting](#Troubleshooting)

---

## **Why do I need to whitelabel the desktop web app?**

  
By whitelabeling your desktop web app, your customers will be using your domain when logging in and using the app. For example, instead of "app.gohighlevel.com" they would use "app.myawesomedomain.com". 

  
**Note** **:** Custom/Whitelabel Domain is the domain you own and your customers will use to log into the desktop app (e.g., [app.yourdomain.com](http://app.yourdomain.com)). HighLevel Default Domain is the temporary GoHighLevel–provided address (e.g., [yourcompany.gohighlevel.com](http://yourcompany.gohighlevel.com)).

---

## **How to Whitelabel the Desktop App**

  
To get started, you'll just need to complete **four easy steps**:

1. Create a CNAME in your DNS records (typically at your domain provider) pointing to **whitelabel.ludicrous.cloud** for example at GoDaddy it might look like this: (the Host field is the prefix you'd like to use before your domain. It can be anything, but in this example, it is "app," meaning "app.myawesomedomain.com" would point to the HighLevel servers.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155023784682/original/Ie-1UZh8nMPlnU-wV7sYKpMeuSnkym6LGg.png?1711981255)
2. Log into your HighLevel Agency account and enter the subdomain as configured in the previous step. Go to the "Agency View" in the sub-account chooser at the top of the side navigation bar > "Settings" > "Company" > "Whitelabel Domain". Scroll down and click the "Update Company" button to save.  
    
![](https://cdn.filestackcontent.com/SvSJP1VTeimnO8kH6zlK)  
    
NOTE: If you previously set up your white-label domain and you want to update it to run on whitelabel.ludicrous.cloud, you'll need to first delete the whitelabel domain field using the trash icon, then click Update Company to save, then re-enter your sub-domain into the Whitelabel Domain field and save again.
3. Upload your agency logo. Within the "Agency View," go to "Settings" > "Agency Settings" > "Company Logo"
4. Update your agency Terms & Conditions. Within the "Agency View," go to "Settings" > "Agency Settings" > "Terms & Conditions URL"  
   * Include the full URL to your Terms & Conditions page, which should look something like this: [](https://myawesomedomain)<https://myawesomedomain.com/terms>

Once your DNS record propagates (typically within a few minutes at most), you can access your new domain, for example: "<https://app.myawesomedomain.com>" and you will see your login screen, logo and terms & conditions. 

  
**Congrats you're done!**

---

## **Troubleshooting**

  
Troubleshooting Whitelabel domain issues often comes down to verifying DNS settings and ensuring SSL has been properly issued. Below are common issues and how to resolve them:

  
* **Error: "The client and server don't support a common SSL protocol version or cipher suite"**  
    
This means the browser or device is using outdated security protocols. HighLevel supports TLS 1.2 and 1.3 only. Update your browser and ensure there are no conflicting DNS records (e.g., both A and CNAME for the same subdomain), which can block SSL from provisioning.

  
* **Domain Not Loading**  
    
Double-check that your subdomain is pointed to the correct CNAME: `app.msgsndr.com`. It may take up to 30 minutes for DNS changes to propagate globally.

  
* **"Your Connection Is Not Private" or HTTPS Not Working**  
    
This usually means your SSL certificate hasn’t been issued yet. Make sure your DNS is fully propagated and pointed only to a single CNAME. Once DNS is correct, SSL is issued automatically via Let's Encrypt.
  
  