**Date Updated:** 2025-05-20T17:41:33.000Z

Group admins can now inject custom JavaScript (JS), Cascading Style Sheets (CSS), and HyperText Markup Language (HTML) code into their groups. This allows for unprecedented levels of customizations

---

**TABLE OF CONTENTS**

* [How to Customize Your Groups](#How-to-Customize-Your-Groups)  
   * [Step 1: Access Client Portal Settings](#Step-1%3A-%C2%A0Access-Client-Portal-Settings)  
   * [Step 2: Access the Branding Tab](#%E2%80%8BStep-2%3A-Access-the-Branding-Tab)  
   * [Step 3: Adding Custom Code](#Step-3%3A%C2%A0-Adding-Custom-Code)  
   * [Step 4: Preview Your Changes](#Step-4%3A%C2%A0Preview-Your-Changes)  
   * [Step 5: Go Live](#Step-5%3A%C2%A0Go-Live)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

## **How to Customize Your Groups**

Follow these steps to add custom code to your groups:

### **Step 1:** Access Client Portal Settings

  
Navigate to your Subaccount → Memberships Tab → Client Portal → Settings 

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046549799/original/O0tDN3A3EB6wVdj5PIkCfvtRXllQp9mhbw.gif?1747141789)

### **Step 2:** Access the Branding Tab

  
Within the Client Portal Settings, click on Branding and scroll down to the Advanced Tab for Custom CSS, Custom JS, and Tracking Code ( for both Header and Footer)

### ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046550162/original/kA_znQIhQG_7Qtj0Wq362J4Ds3Lw7qpvqg.gif?1747142017)
  
  
### **Step 3:** Adding Custom Code

  
* **HTML:** You can add custom HTML to modify the structure or content of your group's pages. This is ideal for adding custom headers, footers, or unique content blocks.
* **CSS:** Use CSS to alter the visual style of your group. This can include changes to colors, fonts, layouts, and more, allowing you to align the group's appearance with your brand or preferences.
* **JS:** JavaScript can be used to add interactive elements or functionality to your group. This could range from simple animations to complex features like custom forms or integrations.

### **Step 4:** Preview Your Changes

  
Before making your customizations live, take advantage of the preview feature. This allows you to see how your custom code affects the group's appearance and functionality, letting you make adjustments as needed without affecting the live site.  

### **Step 5:** Go Live

  
Once you're satisfied with your customizations, save your changes to make them live for all group members. Enjoy your new person

---

## **Frequently Asked Questions**

  
**Q: How do I check how my group looked before adding the code**

* Check how the group looks without a CustomCode via this [Link](CustomCode%20Enable%20Link%20https%3A//test-version-customcode.staging.clientclub.net/communities/groups/test1/home?customCode=true)
* Check how the group looks with a CustomCode via this [Link](https://test-version-customcode.staging.clientclub.net/communities/groups/test1/home?customCode=true)
  
  
**Q: What should I do if I'm experiencing issues in a community after applying custom code?**

If you encounter any problems within a community where custom HTML, CSS, or JavaScript has been implemented, it's important to isolate whether the issue is being caused by the custom code. To do this, you can temporarily disable the custom code and see if the problem still occurs. Simply add 'customCode=false' to the end of the community's URL in your browser's address bar and press Enter. This action deactivates the custom code for your current session, allowing you to check if the issue persists without the customizations. If the problem is resolved with custom code disabled, it indicates that adjustments to your custom code may be necessary.

  
**Q: How can I apply different styles for dark mode vs. light mode in my community portal?**

To target night mode (dark theme) styles specifically, use the .dark class in your CSS. This class is automatically applied to the root when night mode is active.

Avoid using overly broad selectors like div:nth-of-type(2) unless you’re absolutely sure it won’t impact other parts of the page. Always preview and test both modes to ensure visual consistency.